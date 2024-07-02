---
title: About
slug: about
sections:
  - type: GenericSection
    subtitle: ''
    text: ''
    actions: []
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
        padding:
          - pt-1
          - pb-1
          - pr-0
          - pl-1
      subtitle:
        textAlign: left
    media:
      type: ImageBlock
      url: /images/compressed_animated_banner.gif
      altText: Image alt text placeholder
      elementId: ''
      styles:
        self:
          borderRadius: medium
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
