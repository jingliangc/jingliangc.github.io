---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "2rem"


sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Resume
      #   url: uploads/jing_resume.pdf
    design:
      css_class: light
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: background.png
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: true

  - block: collection
    id: project
    content:
      title: Projects
      count: 10
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 3
  
  - block: collection
    id: recent-news
    content:
      count: 10
      title: 'Recent News'
      subtitle: ''
      filters:
        folders:
          - news
    design:
      columns: '1'
      view: short_list
      
  - block: collection
    id: preprints
    content:
      count: 10
      title: Papers Under Submission
      filters:
        folders:
          - indoor_navigation
          - outdoor_navigation
          - place_recognition
          - scene_understanding
          - datasets
          - social_navigation
        exclude_future: false
        exclude_featured: true
        sort_by: 'Date'
    design:
      view: preview

  - block: collection
    id: papers
    content:
      count: 100
      title: Publications
      text: ""
      filters:
        folders:
          - indoor_navigation
          - outdoor_navigation
          - place_recognition
          - scene_understanding
          - datasets
          - social_navigation
        exclude_future: false
        # exclude_featured: false
        featured_only: true
        sort_by: 'Date'
    design:
      view: preview  # citation
---
