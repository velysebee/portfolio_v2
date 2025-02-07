---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: vanessa buice
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: 'story, animation, production'
    text: |
      ![](/images/selfDoodle_transparent3.png)
    actions: []
    media:
      type: VideoBlock
      title: demo reel
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
        padding:
          - pt-5
          - pb-5
        margin:
          - mt-1
          - mb-1
      subtitle:
        textAlign: left
  - type: FeaturedItemsSection
    subtitle: ''
    items:
      - type: FeaturedItem
        title: ''
        tagline: ''
        subtitle: ''
        text: |+
          ### [animation](/animation)

        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-5
              - pl-8
              - pb-5
              - pr-8
            borderRadius: x-large
            flexDirection: col
            textAlign: center
            justifyContent: center
      - type: FeaturedItem
        title: ''
        tagline: ''
        subtitle: ''
        text: |+
          ### [storyboards](/storyboards)

        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-5
              - pl-8
              - pb-5
              - pr-8
            borderRadius: x-large
            flexDirection: col
            textAlign: center
            justifyContent: center
      - type: FeaturedItem
        title: ''
        tagline: ''
        subtitle: ''
        text: |+
          ### [illustration](/illustration)

        image:
          type: ImageBlock
          url: /images/abstract-feature3.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-5
              - pl-8
              - pb-5
              - pr-8
            borderRadius: x-large
            flexDirection: col
            justifyContent: center
            textAlign: center
    actions: []
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-12
          - pl-8
          - pb-12
          - pr-8
        justifyContent: center
        margin:
          - mb-0
      subtitle:
        textAlign: center
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
