---
title: Careers
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-h
    title: Galería
    subtitle: Estos son algunos trabajos realizados
    media:
      type: ImageBlock
      url: /images/hero-4.jpg
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - elementId: ''
    colors: colors-h
    quote: >
      ## *No haces fotografía sólo con la cámara. La haces con todas las
      imágenes que has visto, con todos los libros que has leído, con toda la
      música que has escuchado, y con toda la gente a la que has amado*
    name: Ansel Adams
    title: Padre de la fotografía
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-36
        justifyContent: center
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center
    type: QuoteSection
  - elementId: ''
    colors: colors-a
    images:
      - type: ImageBlock
        url: /images/careers.jpg
        altText: People in the meeting room
      - type: ImageBlock
        url: /images/post-2.jpg
        altText: People in the meeting room
    spacing: 3
    columns: 2
    aspectRatio: '1:1'
    imageSizePx: 400
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
    type: MediaGallerySection
  - elementId: contact-form
    colors: colors-f
    backgroundSize: inset
    title: 'Si te interesa mi trabajo, trabajemos juntos.'
    text: |
      Hablemos, cuéntame lo que necesitas.
    form:
      type: FormBlock
      variant: variant-a
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: primer nombre
          label: Your first name
          hideLabel: true
          placeholder: First name
          isRequired: false
          width: 1/2
        - type: TextFormControl
          name: last-name
          label: Your last name
          hideLabel: true
          placeholder: Last name
          isRequired: false
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Your email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
        - type: TextFormControl
          name: address
          label: Your address
          hideLabel: true
          placeholder: Address
          isRequired: false
          width: full
      submitLabel: Enviar
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-24
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: center
      text:
        textAlign: center
    type: ContactSection
---
