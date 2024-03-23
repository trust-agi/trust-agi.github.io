---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        TrustAGI
         Lab
      image:
        filename: conf.jpg
      text: |
        <br>
        
        The **Trustworthy AGI (TrustAGI) Lab** at [Griffith University](https://www.griffith.edu.au/) is at the forefront of pioneering research in _Artificial General Intelligence (AGI)_, focusing on developing ethical, reliable, and safe AI technologies. This leading lab is dedicated to advancing the understanding and application of AGI through innovative projects, publications, and collaborations. 
        
        

  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 4
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
      view: list
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
          filename: team.jpg
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

      