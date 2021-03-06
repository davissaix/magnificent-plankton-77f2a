---
title: FAQ
layout: PageLayout
sections:
  - elementId: ''
    showDate: true
    title: Publicaciones Recientes
    variant: variant-b
    colors: colors-a
    posts:
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
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
          - pt-12
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-start
    type: FeaturedPostsSection
    actions:
      - altText: ''
        url: /blog
        showIcon: true
        icon: arrowRight
        iconPosition: right
        elementId: ''
        type: Link
        label: See all posts
  - type: ContactSection
    colors: colors-f
    backgroundSize: inset
    title: Contáctame
    text: |
      Escríbeme y con gusto responderé a tus solicitudes.
    form:
      type: FormBlock
      variant: variant-b
      elementId: contact-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: email
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
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
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      text:
        textAlign: center
---
