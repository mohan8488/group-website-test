---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Welcome to **So**ft **M**atter **eX**periment Lab
      image:
        filename: welcome-500px.gif
      text: |
        led by <a style="text-decoration:none;" href="http://localhost:1313/author/roberto-cerbino/">Prof. Roberto Cerbino</a>!  
        From exploring the behavior of polymers and colloids to investigating the dynamics of biological systems, we are dedicated to unraveling the complexities of **Soft** materials. Whether you're a seasoned researcher or an aspiring scientist, we invite you to join us on this exciting journey of discovery.
        {style="text-align: justify;"}
  
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
      columns: '2'
  
  - block: markdown
    content:
      title: 
      subtitle: ''
      text: 
    design:
      columns: '1'
      background:
        image: 
          #caption: Easter Lunch 2024
          filename: group1.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
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