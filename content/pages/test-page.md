---
type: PageLayout
title: html test page
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Chasing Butterflies
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: ''
    text: >+
      <div class="powr-slideshow" id="d810fa62_1720065840"></div><script
      src="https://www.powr.io/powr.js?platform=html"></script>

    actions: []
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
        padding:
          - pt-8
          - pb-1
      subtitle:
        textAlign: left
  - type: GenericSection
    title:
      type: TitleBlock
      text: Business Consulting
      color: text-dark
    subtitle: Be in good company
    text: >
      A service that provides advice and guidance to startups and small
      businesses.
    actions:
      - type: Button
        label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
      - type: Link
        label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    media:
      type: ImageBlock
      url: /images/hero3.svg
      altText: Dope design preview
    badge:
      type: Badge
      label: This is a badge
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
slug: test-page
isDraft: false
seo:
  type: Seo
  metaTitle: Landing Page
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
