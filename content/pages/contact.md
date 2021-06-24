---
title: Daniel Felipe Diaz Rodriguez
hide_title: false
sections:
  - type: section_form
    content: |
      # ¿Quién soy?
       Soy colombiano actualmente me encuentro estudiando la carrera de electrónica en la universidad del valle estando en la universidad conocí en mundo de la programación y decidí como ser más afondo este mundo así que comencé a estudiar programación en Platiz

       # Enfocado en
       Circuitos electrónicos, JavaScript, Python,

       # Trayectoria
       Llevo 2 años en la universidad del valle en la carrera de electrónica, enfocado en Platiz asiendo cursos y retos los cuales puedes observar en mi perfil de LinkedIn 


    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: lorem-ipsum
        label: #Enfocado
        options:
          - null
        is_required: false
        type: form_field
        default_value: #Circuitos electrónicos, JavaScript, Python, 
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
