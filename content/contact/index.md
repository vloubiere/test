---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |
        <p>
        The <strong> Institute of Human Genetics (IGH, UMR 9002) </strong> is located in Montpellier, in the south of France, and is affiliated to the french National Center for Scientific Research (CNRS) and to the University of Montpellier (UM). <br><br>
          <a class="btn btn-primary" href="https://www.igh.cnrs.fr/en" target="_blank">
            <i class="fas fa-external-link-alt"></i> Institute Website
          </a>
        </p>
      email: test@example.org
      phone: +33 4 34 35 99 70
      address:
        street: 141 Rue de la Cardonille 
        city: Montpellier
        region: Hérault
        postcode: '34094 cedex 5'
        country: France
        country_code: FR
      coordinates:
        latitude: '43.635302635500885'
        longitude: '3.847264926015239'
      directions: Enter from the west side of the campus and head to the IGH building, first stair.
      
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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
      columns: '1'
      css_class: contact-page

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      css_class: fullscreen
---
