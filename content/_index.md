---
title: Home
sections:
  - type: form_section
    content: >-
      ## Let's talk


      If you would like more information about my services and pricing, please
      contact me using the form below.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
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
seo:
  title: 'Cloudhealy: Upload'
  description: Upload your files to IPFS protocol from cloudhealy.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: 'Cloudhealy: Upload'
      keyName: property
    - name: 'og:description'
      value: Upload your files to IPFS protocol from cloudhealy.
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: 'Cloudhealy: Upload'
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
