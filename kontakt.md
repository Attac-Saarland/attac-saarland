---
title: Spendenaufruf
hide_title: true
sections:
  - type: form_section
    section_id: contact-form
    title: Spendenaufruf
    subtitle: Einverständniserklärung
    content: >
      Wenn Sie eine Frage haben oder einen Termin für ein Erstgespräch
      vereinbaren möchten, senden Sie mir eine Nachricht.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Ihr Name
        is_required: true
      - input_type: email
        name: email
        label: E-Mail
        default_value: Ihre E-Mail-Adresse
        is_required: true
      - input_type: tel
        name: phone
        label: Telefonnummer
        default_value: Ihre Telefonnummer
        is_required: true
      - input_type: textarea
        name: message
        label: Ihre Nachricht
        default_value: Geben Sie hier Ihre Nachricht ein
        is_required: true
      - input_type: checkbox
        name: consent
        label: >-
          Ich habe die <a href="/datenschutz">Datenschutzbestimmungen</a>
          gelesen und erkenne sie an.
        is_required: true
    submit_label: Nachricht senden
seo:
  title: Kontakt
  description: Dies ist die Kontaktseite
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Kontakt
      keyName: property
    - name: 'og:description'
      value: Dies ist die Kontaktseite
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Kontakt
    - name: 'twitter:description'
      value: Dies ist die Kontaktseite
layout: advanced
---
