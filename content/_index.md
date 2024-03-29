---
title: 'Home'
date: 2024-3-1
type: landing

design:
  # Default section spacing
  spacing: "3rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV (pdf)
        url: uploads/YueyangGuo_CV.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  #- block: markdown  # email and phone
  #  id: contact
  #  content:
  #    title: ""
  #    subtitle: ""
  #    text: |
  #     [pika1218@student.ubc.ca](mailto:pika1218@student.ubc.ca)   
  #      [+1 236.865.6921](tel:+12368656921)
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: skills
    content:
      title: Skills
      username: admin
  #- block: awards
  #  content:
  #    title: Awards
  #    username: admin
  - block: languages
    content:
      title: Languages
      username: admin
  - block: markdown
    title: 'WORK EXPERIENCE'
    subtitle: 'Diebian Aspiration - Planner'
    content: |
      - Communicated with college entrance examination candidates and helped establish the future career development plan.
      - Searched for a large amount of university information suitable for the students such as ranking, location and enrollment score, etc.
      - Assisted in logging in and operating the college application system.
---
