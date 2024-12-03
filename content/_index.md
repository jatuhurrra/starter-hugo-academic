<!-- ---
# Projects section using the Portfolio widget
widget: portfolio
headless: true  # This file represents a page section.
active: true  
weight: 30  # Changed to match projects menu weight in menus.yaml

title: Projects
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  filter_button:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: ''

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact (small card)
  #   3 = Card (large card)
  #   4 = Citation (publication only)
  view: 3   # Changed to card view for better project display

  # Flip alternate rows for Showcase view
  flip_alt_rows: false
--- -->

---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  <!-- - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin -->
    
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