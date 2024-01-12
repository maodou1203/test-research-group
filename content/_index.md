---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
  - block: experience
    content:
      title: Working Experience
      items:
        - title: Associate Professor
          company: Macao Polytechnic University
          company_url: 'https://www.mpu.edu.mo/zh/index.php'
          company_logo: org-mpu
          location: Macau
          date_start: '2021-08-19'
          date_end: ''
      
        - title: Assistant Professor & Associate Professor
          company: Macau University of Science and Technology
          company_url: 'https://www.must.edu.mo/en'
          company_logo: org-must
          location: Macau
          date_start: '2016-01-11'
          date_end: '2021-07-31'
      
        - title: Postdoctoral Fellowship
          company: University of Macau
          company_url: 'https://www.um.edu.mo/'
          company_logo: org-um
          location: Macau
          date_start: '2014-02-01'
          date_end: '2015-10-31'
          
        - title: Research Assistant
          company: University of Macau
          company_url: 'https://www.um.edu.mo/'
          company_logo: org-um
          location: Macau
          date_start: '2013-11-01'
          date_end: '2014-01-31'
    design:
      columns: '2'
        
  
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
      view: compact
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
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
