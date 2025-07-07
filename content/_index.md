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
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I'm deeply passionate about AI and its applications in biomedical informatics. My current research focuses on improving contextual understanding in sentence classification of medical abstracts using transformer-based models.

        I've recently published a paper that integrates BERT embeddings, character-level BiLSTM processing, and abstract structure features to outperform prior models on the PubMed 20k dataset.

        Please feel free to connect for collaboration or research discussions!
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publication
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 1
---
