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
        text: Download Résumé (pdf version)
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: buttons
    content:
      buttons:
        - title: Read my latest paper on LLMs
          icon: brands/arxiv
          url: https://arxiv.org/abs/2304.01852
        - title: Watch my new YouTube video to achieve 20x productivity
          icon: brands/youtube
          url: https://youtube.com
        - title: Connect with me on LinkedIn
          icon: brands/linkedin
          url: https://linkedin.com
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
---
