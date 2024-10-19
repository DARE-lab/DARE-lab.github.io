---
# Leave the homepage title empty to use the site title
title:
date: 2024-01-07
type: landing

sections:
  - block: hero
    content:
      title: |
        Digital Archaeology Research Environment
      image:
        filename: icon.png
      text: |
        <br>
        
        **DARE** creates social and intellectual space to examine, build and develop anti-colonial, anti-racist digital and geospatial methods, tools, technologies, pedagogies, capacities, practices and policies, with particular focus on heritage and social sciences. We are located in the Arts and Sciences building at the University of British Columbia, Okanagan, on the unceded, ancestral lands of the syilx/Okanagan people.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: desktop.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['10px', '0', '10px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---