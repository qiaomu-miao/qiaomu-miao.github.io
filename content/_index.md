---
# Leave the homepage title empty to use the site title
title: ""
type: landing
cms_exclude: true

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
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
    design:
      css_class: light
      background:
        color: 'FloralWhite'
        text_color_light: false
        image:
          # Add your image background to `assets/media/`.
          #filename: stacked-peaks.svg
          filename: ''
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: collection
    id: publication
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
      count: 8
      sort_by: 'weight'
      sort_ascending: true
    design:
      view: citation
  
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 2
      image:
        size: contain

  - block: markdown
    id: experience
    content:
      title: Experience
      text: |-
        <br>
        <font size="4"> 
        <div style="display: flex; justify-content: space-between; margin: 0; padding: 0;">
        <span><strong>Student Researcher</strong></span>  <span><span style="color:gray">Sep 2025 - Present</span></span></div>
        </font>
        <font size="3">
        <div style="display: flex; align-items: center; margin: 0; padding: 0;">
          <img src="experience/Google_logo.svg" width="30" height="30" style="margin-right: 20px;">
          <p style="margin: 0;">Google</p>
        </div>
        
          <div style="margin: 0; padding: 0;">
          <ul style="margin: 0;">
          <li> Developing eye segmentation and eye-tracking pipelines with large foundation models. </li>
          </ul>
          </div>
        </font>
        <br><br>
        <font size="4"> 
        <div style="display: flex; justify-content: space-between; margin: 0; padding: 0;">
        <span><strong> Technology Investigation Intern </strong></span>  <span><span style="color:gray">May 2022 - Aug 2022</span></span></div>
        </font>
        <font size="3">
        <div style="display: flex; align-items: center; margin: 0; padding: 0;">
          <img src="experience/Apple_logo.svg" width="30" height="30" style="margin-right: 20px;">
          <p style="margin: 0;">Apple</p>
        </div>
        
          <div style="margin: 0; padding: 0;">
          <ul style="margin: 0;">
          <li> Designed and trained activity recognition models on video datasets for augmented reality (AR) applications </li>
          <li> Improved activity recognition performance by incorporating scene understanding concepts </li>
          </ul>
          </div>
        </font>
        <br><br>
        <font size="4"> 
        <div style="display: flex; justify-content: space-between; margin: 0; padding: 0;">
        <span><strong> Research Intern </strong></span>  <span><span style="color:gray">Jun 2021 - Aug 2021</span></span></div>
        </font>
        <font size="3">
        <div style="display: flex; align-items: center; margin: 0; padding: 0;">
          <img src="experience/bytedance-color.svg" width="30" height="30" style="margin-right: 20px;">
          <p style="margin: 0;">Bytedance</p>
        </div>
          <div style="margin: 0; padding: 0;">
          <ul style="margin: 0;">
          <li> Generated motion-transferred DeepFake videos with state-of-the-art lipsyncing and face reenactment models to investigate the behavioral signatures (speaking style and utterance, etc.) in person identification </li>
          <li> Implemented a self-supervised DeepFake Detection model using behavioral and appearance-related features </li>
          </ul>
          </div>
        </font>
---