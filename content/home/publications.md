---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: collection

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Publications
subtitle: ''

content:
  # Filter on criteria
  filters:
    folders:
      - publication
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 5
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
Publication list also available [on Google Scholar](https://scholar.google.com/citations?user=-V3CmPoAAAAJ&hl=en).
{{% /callout %}}