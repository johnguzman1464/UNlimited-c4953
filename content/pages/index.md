---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: 'Impulsando Capacidades, No Barreras'
      color: text-dark
      type: TitleBlock
    subtitle: Unlimited
    text: >
      Nuestra plataforma ofrece y visibiliza múltiples opciones para que las
      personas con discapacidad puedan conseguir alternativas viables para tener
      una independencia económica junto con un trabajo o emprendimiento estable.
    actions:
      - label: Registrarse
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: Quienes Somos
        altText: ''
        url: /careers
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - title:
      text: ¿Que ofrecemos?
      color: text-light
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Oportunidades para las personas con discapacidad
    items:
      - title: Organizaciones
        tagline: ''
        subtitle: Conoce organizaciones
        text: >
          Que apoyan a las personas con discapacidad, para que puedan tener un
          trabajo de calidad.
        image:
          url: /images/abstract-feature1.svg
          altText: Placeholder Image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - type: Link
            label: Ver Organizaciones
            altText: ''
            url: /blog
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
      - title: Historias
        tagline: ''
        subtitle: Lee historias de éxito
        text: |
          De personas con discapacidad en el mundo laboral.
        image:
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - type: Link
            label: Ver historias
            altText: ''
            url: /hist
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
      - title: Emprendimientos
        tagline: ''
        subtitle: Conoce emprendimientos
        text: |
          Creados por personas con discapacidad y sus cuidadores.
        image:
          url: /images/abstract-feature1.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - type: Link
            label: Proximamente
            altText: ''
            url: /home
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
    variant: three-col-grid
    colors: bg-dark-fg-light
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Business Consulting
      color: text-dark
      type: TitleBlock
    subtitle: Be in good company
    text: >
      A service that provides advice and guidance to startups and small
      businesses.
    actions:
      - label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero3.svg
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: This is a badge
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
  - title:
      text: Regístrate Ahora
      color: text-dark
      type: TitleBlock
    subtitle: Para...
    text: |
      (describir beneficios).
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Nombres y Apellidos
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Correo Electrónico
          isRequired: true
          width: full
          type: EmailFormControl
        - type: TextFormControl
          name: cel
          label: cel
          hideLabel: true
          placeholder: Telefono
          isRequired: true
          width: full
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Enviar
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: CONTACTANOS
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
