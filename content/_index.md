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
          filename: groupwork.jpg
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
        {{% cta cta_link="./people/current-people" cta_text="Meet the team →" %}}
    design:
      columns: '1'
      
  - block: markdown
    content:
      title: Vacanct positions
      subtitle:
      text: We are recruiting the self-motivated Ph.D. and master students. If your are interested in our work, please send an email to us.
    design:
      view: compact
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: xcyuan@mpu.edu.mo
      phone: +853-85996434
      address:
        street: R. de Luís Gonzaga Gomes
        city: Macau 
    
    
      coordinates:
        latitude: '22.1936'
        longitude: '113.5518'
      directions: Office A313, Chi Un Building
      office_hours:
        - ''

      # Choose a map provider in `params.yaml` to show a map from these coordinates
#      coordinates:
#        latitude: '22.1936'
#        longitude: '113.5518'
#      directions: Office A313, Chi Un Building
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
