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
      is_education_first: true
  - block: markdown
    content:
      title: 'Industrial Experience'
      items:
    - title: "Design Engineer"
      company: "ABB Robotics"
      location: "Your Location"
      date_start: "2022-01-01"
      date_end: "2023-12-31"
      description: |-
        - Designed end-effectors for manipulators
        - Developed welding fixtures
        - Performed design validation
        
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
  - block: resume-languages
    content:
      title: Languages
      username: admin
---
