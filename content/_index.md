<style>
  a { color: #0F52BA !important; }
</style>
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
      # Show a call-to-action button under your biography? (optional)
      #button:
        #text: Download CV
        #url: uploads/resume.pdf
    #design:
      #css_class: light
      #background:
        #color: white
        #image:
          # Add your image background to `assets/media/`.
          #filename: stacked-peaks.svg
          #filters:
            #brightness: 1.0
          #size: cover
          #position: center
          #parallax: false
  #- block: markdown
    #content:
      #title: '📚 My Research'
      #subtitle: ''
      #text: |-
        #Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        #I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
        #Please reach out to collaborate 😃
    #design:
      #columns: '1'

  - block: markdown
    id: awards
    content:
      title: 'Awards'
      #subtitle: ''
      text: |-
        <div style="font-size: 1rem; white-space: nowrap;">
          <div style="white-space: nowrap;">• ACM/IEEE IPSN 2024 Best Artifact Runner-up Award, May 2024</div>
          <div style="white-space: nowrap;">• Google Networking Research Summit 2023 Invited Attendee, Nov. 2023</div>
          <div style="white-space: nowrap;">• EECS Rising Stars Workshop 2023 Invited Attendee, Nov. 2023</div>
          <div style="white-space: nowrap;">• NSF Athena 2023 Annual Session Best Poster Runner-up Award, May 2023</div>
          <div style="white-space: nowrap;">• Cyber-Physical Systems (CPS) Rising Stars Workshop 2023 Invited Attendee, May 2023</div>
          <div style="white-space: nowrap;">• IEEE INFOCOM 2023 Student Travel Grant, April 2023</div>
          <div style="white-space: nowrap;">• IEEE INFOCOM 2022 Student Travel Grant, May 2022</div>
          <div style="white-space: nowrap;">• ACM SenSys 2019 NSF Student Travel Grant, Nov. 2019</div>
        </div> 
    design:
      columns: '1'

  #- block: collection
    #id: papers
    #content:
      #title: Featured Publications
      #filters:
        #folders:
          #- publication
        #featured_only: true
    #design:
      #view: article-grid
      #columns: 2
  #- block: collection
    #content:
      #title: Recent Publications
      #text: ""
      #filters:
        #folders:
          #- publication
        #exclude_featured: false
    #design:
      #view: citation
  #- block: collection
    #id: talks
    #content:
      #title: Recent & Upcoming Talks
      #filters:
        #folders:
          #- event
    #design:
      #view: article-grid
      #columns: 1

---
