---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"
  
sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)

    design:
      css_class: dark
      background:
        color: DimGray
        image:
          # Add your image background to `assets/media/`.
          filename:
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '🔍 My Research'
      subtitle: ''
      text: |-
        I am drawn to questions that resist quick answers—those that unfold through ambiguity, contradiction, and quiet resistance.

        I believe that understanding organizations begins with understanding how people search for meaning when the world stops making sense, and how heterogeneous forms of cognition shape that search.
        
        I work with deliberate care, seeking ideas that are both structurally precise and deeply human.

        If we accept only what we can predict as knowledge, then we must erase the legacy of Max Weber, discard the paradigm shifts of Thomas Kuhn, and silence the insights of Carl Jung and Friedrich Nietzsche.
        
        But we haven’t—because we know that knowledge is not only about accuracy, but about meaning. And organization theory is where meaning finds structure.
    design:
      columns: '1'

  - block: collection
    id: research
    content:
      title: Research in Progress
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
---
