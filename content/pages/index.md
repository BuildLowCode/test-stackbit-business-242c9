---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-b
    backgroundSize: full
    title: Software to Manage Gyms and Access Control
    subtitle: Customizable. Profesional. Accesible.
    actions:
      - type: Button
        label: Preview
        url: 'https://www.stackbit.com/'
        style: primary
        iconPosition: right
        icon: arrowRight
        showIcon: true
    backgroundImage:
      type: BackgroundImage
      url: /images/pexels-pixabay-260447-bacaa66e.jpg
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 85
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-20
          - pb-96
          - pr-12
          - pl-12
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: QuoteSection
    colors: colors-a
    quote: >
      “The FitGym Software is the best to manage Gyms and access control for my
      clients. It helps reduce costs, save time and manage the business
      efficiently.”
    name: Sue Weaver
    title: Head Manager ProFitnessGym
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pr-4
          - pl-4
        justifyContent: center
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center
  - type: FeaturedItemsSection
    colors: colors-a
    elementId: ''
    title: Key value propositions
    subtitle: ''
    items:
      - type: FeaturedItem
        actions: []
        styles:
          self:
            textAlign: left
        subtitle: >
          FitGym is a software that helps you increase your profits by taking
          care of your gym management. With it, you can:
      - type: FeaturedItem
        title: Manage
        actions: []
        styles:
          self:
            textAlign: left
        subtitle: '- Manage gyms, employees and memberships'
      - type: FeaturedItem
        elementId: ''
        title: Monitor
        subtitle: >-
          - Monitor gym’s finances and operations - Get insights on customer
          behavior and data analytics
        actions: []
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: Track
        text: |
          \- Track all fitness activities and charges in real time 
        actions:
          - type: Button
            label: Learn more
            showIcon: true
            icon: arrowRight
            style: primary
            url: 'https://www.stackbit.com/'
        styles:
          self:
            textAlign: left
    actions: []
    columns: 1
    spacingX: 16
    spacingY: 16
    enableHover: false
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-8
          - pb-32
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: TextSection
    colors: colors-b
    variant: variant-a
    text: >+
      # [Request a Demo
      ](https://test-stackbit-business-242c9.stackbit.app/demo/)

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
          - pt-36
          - pb-36
          - pr-4
          - pl-4
        justifyContent: center
      text:
        textAlign: center
  - type: FeatureHighlightSection
    colors: colors-b
    backgroundSize: full
    title: It's time to put down that messy spreadsheet and join fitGym
    text: >
      Manage, track, charge and monitor with the tools that fitgym offer for
      you.
    actions:
      - type: Link
        label: Learn More
        url: 'https://www.stackbit.com/'
        showIcon: true
        icon: arrowRight
    backgroundImage:
      type: BackgroundImage
      url: /images/pexels-william-choquette-1954524.jpg
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 90
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
          - pb-72
          - pr-4
          - pl-4
        justifyContent: flex-start
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: ContactSection
    colors: colors-c
    elementId: ''
    backgroundSize: full
    title: Get early access
    text: >-
      Sign up your team today to be the first to try out our new product to
      increase your team's productivity.
    form:
      type: FormBlock
      elementId: sign-up-form
      action: /.netlify/functions/submission_created
      destination: buildlowcode@gmail.com
      fields:
        - type: EmailFormControl
          name: email
          placeholder: Your email
          isRequired: 'true'
          width: full
      submitLabel: Sign Up
    media: null
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
addTitleSuffix: true
metaTags: []
---
