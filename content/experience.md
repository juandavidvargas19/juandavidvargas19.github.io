---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
  - block: resume-awards
    content:
      title: Awards
      username: admin
  - block: collection
    content:
      count: 0
      title: Math Olympiads
      text: Over the years I enjoyed logical challenges through math competitions.
      filters:
        folders:
          - experience
    design:
      view: article-grid
      fill_image: false
      columns: 3
  - block: resume-languages
    content:
      title: Languages
      username: admin
---
