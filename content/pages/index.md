---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: '[I CANT CODE ]'
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: |+


    actions: []
    media:
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: HEY FOLKS
      color: text-primary
      type: Badge
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
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: auto
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
  - type: GenericSection
    title:
      text: ''
      type: TitleBlock
    subtitle: ''
    text: |
      <div style="position: relative; width: 100%; height: 100vh; overflow: hidden;">
        <iframe 
          src="https://my.spline.design/animatedbackgroundgradientforweb-jvVyiKfTSuDVJmCJ0QzP2hT6/" 
          frameborder="0" 
          style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; z-index: 0; border: none;">
        </iframe>
        <div style="position: relative; z-index: 1; color: white; display: flex; flex-direction: column; align-items: center; justify-content: center; height: 100vh; text-align: center; padding: 0 1rem;">
          <div style="background: #0070f3; color: white; padding: 0.4rem 1rem; border-radius: 999px; font-weight: bold; margin-bottom: 1rem;">
            HEY FOLKS
          </div>
          <h1 style="font-size: 3rem; margin: 0;">I CANT CODE</h1>
          <p style="font-size: 1.2rem; font-style: italic;">I JUST HAVE THIS DOMAIN CUZ IT WAS FREE</p>
        </div>
      </div>
    actions: []
    media:
      altText: ''
      elementId: ''
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
    elementId: hero-section
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding: []

  - type: FeaturedItemsSection
    title:
      text: blabh blabh
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: woosh
    items:
      - type: FeaturedItem
        title: '-'
        subtitle: '-'
        text: |
          \-
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: '-'
        subtitle: '-'
        text: |+
          \-

        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: '-'
        subtitle: '-'
        text: |+
          \-

        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions: []
    badge:
      label: blabh blabh
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center

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

  - type: GenericSection
    title:
      text: Generic section with a video
      color: text-dark
      styles:
        self:
          textAlign: left
      type: TitleBlock
    subtitle: Section with a video subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
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
      type: VideoBlock
    elementId: null
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left

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

seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
