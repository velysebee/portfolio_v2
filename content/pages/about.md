---
title: About
slug: about
sections:
  - type: ImageGallerySection
    subtitle: ''
    images:
      - type: ImageBlock
        url: /images/compressed_animated_banner.png
        altText: Image alt text placeholder
        elementId: ''
        styles:
          self:
            borderRadius: medium
    elementId: ''
    motion: static
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mt-0
          - ml-0
          - mb-0
          - mr-0
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic section with a video
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: ''
    text: ''
    actions: []
    media:
      type: VideoBlock
      title: Title of the video
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - type: GenericSection
    title:
      type: TitleBlock
      text: Hello!
      color: text-dark
      styles:
        self:
          fontWeight: 400
    subtitle: ''
    text: |
      insert about and bio here
    actions:
      - type: Button
        label: artist resume
        altText: artist resume
        url: /art-resume
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Button
        label: production resume
        altText: production resume
        url: /production-resume
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/VanessaBuice_headshotv2.png
      altText: Headshot of Vanessa Buice
    badge:
      type: Badge
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: left
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
seo:
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
