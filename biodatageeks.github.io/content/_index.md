---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      # title: |
      #   Biodatageeks
      image:
        filename: logo_helix.png
        alt: Biodatageeks Logo
        style: |
          margin-top: 70px;  # Adjust the value to move the image lower
      text: |
        <div style="text-align: center;">
        <br>
        
        **BiodataGeeks** is a research team at Warsaw University of Technology, bringing together faculty, PhD students, and students to explore the frontiers of bioinformatics, genomics, and genetic data analysis. Specializing in next-generation sequencing, we engage in a variety of projects and collaborate with both domestic and international partners to advance knowledge and innovation in the field.
        </div>

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
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
