---
layout: PageLayout
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Empty page
sections:
  - type: TextSection
    colors: colors-d
    variant: variant-a
    title: This in an empty page
    text: >-
      Start adding sections by clicking the + button on the page or through the
      sidebar.
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mb-12
        padding:
          - pt-12
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: ContactSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: Contact us
    text: We look forward to hearing from you.
    form:
      type: FormBlock
      elementId: contact-form
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          placeholder: Your name
          isRequired: 'true'
          width: 1/2
        - type: EmailFormControl
          name: email
          placeholder: Your email
          isRequired: 'true'
          width: 1/2
        - type: TextFormControl
          name: address
          placeholder: Your home address
          isRequired: 'false'
          width: full
        - type: TextareaFormControl
          name: description
          label: Description
          hideLabel: false
          placeholder: Please describe your gym
          isRequired: false
          width: full
      submitLabel: Send Message
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
        textAlign: center
      text:
        textAlign: center
---
