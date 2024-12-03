---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  # - block: about.biography
  #   id: about
  #   content:
  #     title: Biography
  #     # Choose a user profile to display (a folder name within `content/authors/`)
  #     username: admin

  # Add this section to display projects  
  - block: portfolio
    id: projects  # This is important - matches the URL in menus.yaml
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
