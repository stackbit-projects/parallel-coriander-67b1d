---
title: Blogas
sections:
  - type: hero_section
    title: Blogas
    subtitle: 'Deja, šiuo metu jokių įrašų nėra.'
    align: center
    padding_top: medium
    padding_bottom: none
    background_color: none
  - type: form_section
    title: Norite sekti naujienas?
    title_align: center
    content: |
      Prenumeruokite ir būsite informuoti kai įkelsime naujus įrašus.
    content_align: center
    form_position: bottom
    form_layout: inline
    form_id: subscribeForm
    form_action: /thank-you
    form_fields:
      - input_type: email
        name: email
        label: Email
        default_value: Jūsų el. part adresas
        is_required: true
    submit_label: Prenumeruoti
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: secondary
  - type: blog_feed_section
    blog_feed_cols: three
    enable_cards: true
    show_recent: false
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: true
    show_image: true
    padding_top: small
    padding_bottom: large
    has_border: true
template: advanced
---
