---
title: Home
sections:
  - type: hero_section
    title: '"Tyler is a skilled optimist."'
    subtitle: >-
      Skilled optimism is the belief that people can acquire and use skills to
      make the world a better place.
    actions:
      - label: Read the Essay
        url: /contact
        style: primary
      - label: Become a Skilled Optimist
        url: '#'
        style: link
        has_icon: false
        icon: arrow-left
        icon_position: right
        new_window: false
        no_follow: false
        type: action
    image: images/personal site.png
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: features_section
    title: What I help people do
    subtitle: Optimism in action
    features:
      - title: Make Better Decisions
        subtitle: Unsupervised helps companies use their data to make better decisions.
        content: >
          I co-founded [Unsupervised](https://unsupervised.com/) in 2017. Our AI
          helps you find the best ways to improve any KPI, by automatically
          analyzing 1000x more data and identifying your best opportunities. In
          Q1 of 2021, we helped our customers grow their revenue and profit by
          millions of dollars.
        actions:
          - label: Visit Unsupervised.com
            url: 'https://unsupervised.com/'
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
            new_window: true
        image: images/feature-1.svg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
      - title: Invest in Startups
        subtitle: 'Product updates, inventory and pricing.'
        content: >-
          Managing an online business is a full-time job. I will make sure your
          products look great, sound great, and sell more on your choice of
          ecommerce platform.
        actions:
          - label: Learn More
            url: /about
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-2.svg
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
      - title: Technical Content
        subtitle: 'Your products and services, at scale.'
        content: >-
          I will dive into the ins and outs of your product or service and make
          sure the right information is communicated throughout your
          documentation, pamphlets, manuals and technical documents.
        actions:
          - label: See Past Work
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-3.svg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: grid_section
    title: Trusted by Companies Big and Small
    subtitle: Companies I've worked with
    align: center
    grid_items:
      - image: images/logo-1.svg
        image_alt: Logo 1
        image_align: center
      - image: images/logo-2.svg
        image_alt: Logo 2
        image_align: center
      - image: images/logo-3.svg
        image_alt: Logo 3
        image_align: center
      - image: images/logo-4.svg
        image_alt: Logo 4
        image_align: center
      - image: images/logo-5.svg
        image_alt: Logo 5
        image_align: center
      - image: images/logo-6.svg
        image_alt: Logo 6
        image_align: center
      - image: images/logo-7.svg
        image_alt: Logo 7
        image_align: center
      - image: images/logo-8.svg
        image_alt: Logo 8
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
  - type: grid_section
    title: Testimonials
    subtitle: What My Clients Say
    grid_items:
      - content: >-
          Alyvia is an amazing content writer. She helped us produce microcopy
          for our apps in all levels of user touchpoints.


          **Hanson Deck,** *App Developer, Studio*
        image: images/hanson-deck.png
        image_position: left
        image_width: twenty-five
      - content: >-
          Alyvia really understands who our customers are and what tone of voice
          to use when communicating with them.


          **Miles Tone,** *CEO, Studio*
        image: images/miles-tone.png
        image_position: left
        image_width: twenty-five
      - content: >-
          Working with Alyvia was great because she was well versed in all of
          our tools and applications, and was able to manage our store and
          campaigns without any technical glitches.


          **Eleanor Carr,** *CTO, eCommerce Business*
        image: images/eleanor-carr.png
        image_position: left
        image_width: twenty-five
      - content: >-
          I love it when a content writer can really wordsmith and create copy
          that suits the design intention and style!


          **Gordon Norman,** *Web Designer, Local Business*
        image: images/gordon-norman.png
        image_position: left
        image_width: twenty-five
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
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
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Stackbit Personal Theme
  description: The preview of the Personal theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
