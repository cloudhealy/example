---
title: Sign Up
sections:
  - type: hero_section
    title: ¡Gracias por usar Cloudhealy!
    subtitle: Por favor responde la siguiente encuesta.
    align: center
    padding_top: medium
    padding_bottom: none
    background_color: none
  - type: form_section
    form_position: center
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: signup
    form_action: https://docs.google.com/forms/d/e/1FAIpQLSeDoO2ydbzOwOM-JSDclK3qQHds3iLGkRCOucOkdUuGObdNSQ/formResponse
    form_fields:
      - input_type: email
        name: entry.246119456
        label: Correo electrónico*
        default_value: correo@chido.com
        is_required: true
      - input_type: select
        name: entry.449836798
        label: ¿Por qué usaste Cloudhealy?*
        default_value: Selecciona una opción
        options:
          - Conozco muy poco de IPFS
          - Creo que es muy sencillo de utilizar
          - Es muy complicado usar otras herramientas
        is_required: true
      - input_type: select
        name:  entry.1842654360
        label: ¿Qué tipo de archivo subiste?*
        default_value: Selecciona una opción
        options:
          - Texto
          - Imagen
          - Audio
          - Vídeo
          - Un documento PDF, DOC, XLS PTT, PPS
          - Otro
        is_required: true
      - input_type: textarea
        name: entry.1755220641
        label: ¿Qué deberíamos mejorar?
        default_value: Si prefieres no es necesario responder :)
    submit_label: Envíar
    align_vert: top
    padding_top: none
    padding_bottom: medium
    background_color: none
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Encuesta
  description: 
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Encuesta
      keyName: property
    - name: 'og:description'
      value: 
      keyName: property
    - name: 'twitter:card'
      value: Encuesta
    - name: 'twitter:title'
      value: Encuesta
    - name: 'twitter:description'
      value: 
layout: advanced
---
