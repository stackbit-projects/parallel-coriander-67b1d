---
title: Laiškas
sections:
  - type: hero_section
    title: This is the Hero
    subtitle: The optional subtitle
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ### Parašykite mums laišką!


      Norime įspėti, jog į elektroninius laiškus atsakome per 24 valandas. Jeigu
      norite susisiekti skubiai, siūlome kreiptis telefonu.


      ### Privacy


      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
      ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
      fringilla, fringilla.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Vardas
        default_value: Jūsų vardas
        is_required: true
      - input_type: email
        name: email
        label: El. pašto adresas
        default_value: Jūsų el. pašto adresas
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
        label: Žinutė
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
template: advanced
---
