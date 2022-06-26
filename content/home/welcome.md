---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Welcome to the Lab
      content: The **Robotics and Intelligent Vehicles Research Laboratory (RIVeR)** has been at the cutting edge of experiential research since its founding in 2010.
      align: left
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: RIVeR_Home.jpg
    - title: People
      content: 'Our talented team of humans (and robots) is a winning combo!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: RIVeR_friends.jpg
      link:
        icon: user-group
        icon_pack: fas
        text: Meet the Team
        url: ../people/
    - title: Research
      content: 'Our work takes us into the real world as we tackle challenges in multi-modal perception and human-robot teaming.'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: RIVeR_VAST.png
      link:
        icon: atom
        icon_pack: fas
        text: Current Research
        url: ../project/
    - title: Join Us
      content: 'Interested in our work? Want to get involved? Drop us a line.'
      align: left
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: RIVeR_ACE_PROJECT.jpg
      link:
        icon: handshake-angle
        icon_pack: fas
        text: Join Us
        url: ../contact/
---