---
title: Tour
date: 2024-02-24

type: landing

sections:
  - block: portfolio
    id: research
    content:
      title: Featured Projects
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
        - name: Trustworthy AI
          tag: Trustworthy AI
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: masonry #card
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: featured
    content:
      title: Featured Publications
      count: 3
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: masonry
---
