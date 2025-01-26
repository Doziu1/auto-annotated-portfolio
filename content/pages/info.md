---
type: PageLayout
title: Kontakt
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >+
      ## Cześć jeżeli chcesz się z nami skontaktować zadzwoń do nas lub napisz w
      formularzu



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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Kontakt:'
    colors: colors-f
    text: >+
      Masz pytania dotyczące polskiej przyrody? A może chcesz podzielić się
      swoimi obserwacjami lub pomysłami? Zapraszamy do kontaktu! Jesteśmy
      otwarci na współpracę i chętnie odpowiemy na każde pytanie.


      **Dane kontaktowe:**


      *   **Telefon:** 850-123-502


      *   **E-mail:** [amelialawreszuk@gmail.com]()


      *   **Adres:**
          ul. Lipowa 7,
          15-774 Białystok

      **Godziny pracy:**

      Poniedziałek - Piątek: 9:00 - 17:00

      Sobota: 10:00 - 14:00

      Niedziela: Zamknięte



  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Napisz do nas! \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
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
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Co chcesz nam przekazać?
          isRequired: true
          width: full
          type: TextareaFormControl
      submitLabel: " \U0001F680"
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
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
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
