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
    design:
      columns: "1"
    content:
      title: 'Industrial Experience'
      text: |-
        <div style="font-size: 0.9rem;">
        **ABB Robots – Design Engineer**

        I designed end-effectors for manipulators and fixtures for welding components.

        **Key Responsibilities**
        - Designed robot end-effectors for assembly and welding
        - Developed custom welding fixtures
        - Performed tolerance analysis and validation

        </div>

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
