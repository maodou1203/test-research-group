---
#title: Research
date: 2022-10-24

type: landing

sections:
  - block: markdown
    content:
      title: |
      text: |
        # Research
        Our Research Team in the Faculty of Applied Sciences at Macau Polytechnic University is dedicated to research in the field of digital security. Our research spans various aspects of digital multimedia processing, including digital watermarking, multimedia forensics, tampering detection, self-recovery, remote image processing, and the application of deep learning techniques. With a dedication to fostering the progress of artificial intelligence in security, we consistently push the boundaries of our field through innovative research. Our primary objective is to leverage our expertise to address key challenges in the field of digital security.
      
#    design:
#      # Slide height is automatic unless you force a specific height (e.g. '400px')
#      slide_height: ''
#      is_fullscreen: true
#      # Automatically transition through slides?
#      loop: false
#      # Duration of transition between slides (in ms)
#      interval: 2000
  - block: portfolio
    id: project
    content:
      title: Research Areas
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Digital Watermarking
          tag: Digital Watermarking
        - name: Image Self-recovery
          tag: Image Self-recovery
        - name: Deep Learning
          tag: Deep Learning
        - name: AI Security
          tag: AI Security
        - name: Multimedia Forensics
          tag: Multimedia Forensics
        - name: Remote imaging
          tag: Remote imaging
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
