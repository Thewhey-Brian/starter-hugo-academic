---
# Leave the homepage title empty to use the site title
title: Xinyu (Brian) Guo 郭昕育
date: 2022-10-24
type: landing

authors:
- admin

# Is this the primary user of the site?
superuser: true

# Role/position
role: Master Student of Biostatistics

# Organizations/Affiliations
organizations:
- name: Department of Biostatistics, Johns Hopkins University
        Bloomberg School of Public Health
  url: "https://www.jhsph.edu/departments/biostatistics/"

# Short bio (displayed in user profile at end of posts)
bio: My research interests include nonparametric estimation, statistical learning, and bioinformatics.

interests:
- Statistical Genetics And Genomics
- Nonparametric Estimation
- Statistical Learning
- Bioinformatics

education:
  courses:
  - course: ScM in Biostatistics (current)
    institution: Johns Hopkins University
    year: 2021
  - course: BA in Mathematics
    institution: Washington University in St. Louis
    year: 2020

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
---
