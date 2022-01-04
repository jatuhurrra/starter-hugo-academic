---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages
#widget: featured

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 90

#title: Recent Publications
title: Publications
subtitle: ''

content:
  # Filter on criteria
  filters:
    folders:
      - publication
    tag: ''
    category: 'Computer Security'
    publication_type: 'Conference paper'
    author: 'Jesse Atuhurra'
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
design:
  # Choose a view for the listings:
  view: citation
  columns: '2'
---

{{% callout note %}}
Recent publications are available [here](./publication/).
{{% /callout %}}
