---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title: Contributors
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: people
  sort_by: Params.weight
  filter_default: 0
  filter_button:
    - name: All
      tag: '*'
    - name: Keynote speakers
      tag: keynote
    - name: Assistants
      tag: assistant
    - name: Organisers
      tag: organiser

    

design:
  columns: '2'
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---

