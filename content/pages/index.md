---
type: PageLayout
title: Home
colors: colors-a
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Fauna i flora wybranych rejonów Polski
    subtitle: >-
      Poznaj bogactwo przyrodnicze naszego kraju! Dowiedz się więcej o
      unikalnych roślinach i zwierzętach występujących w różnych częściach
      Polski – od górskich lasów Tatr, przez nadmorskie wydmy Bałtyku, aż po
      rozległe równiny Mazowsza. 
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
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - colors: colors-c
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: Zobacz wszystkie wpisy
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
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
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: zobacz co przygotowaliśmy
    title: Nasze wpisy
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: Chciałbyś dostawać więcej informacji o Faunie i Florze w Polsce?
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: Imię
          label: Imię
          hideLabel: true
          placeholder: Imię
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Nazwisko
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Addres
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
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
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
