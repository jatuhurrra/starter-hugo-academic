---
# Projects section using the Portfolio widget
widget: portfolio
headless: true  # This file represents a page section.
active: true  # Activate this widget? true/false
weight: 65  # Order that this section appears on the page.

title: Projects
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Filter options (optional)
  filter_default: 0

  filter_button:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: 'Deep Learning'
    - name: Other
      tag: ''

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---