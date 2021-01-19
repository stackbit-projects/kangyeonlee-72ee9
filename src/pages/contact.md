---
title: 'I hope we can keep in touch :)'
hide_title: false
sections:
  - type: section_form
    template: section_form
    section_id: contact-form
    content: >
      I'm looking for new opportunities! If you are interested in my works or
      blog posts, please contact me at
      [kangyeon.lee.alicia@gmail.com](mailto:example@example.com)
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - type: form_field
        template: form_field
        input_type: text
        name: name
        label: NAME
        default_value: Your name
        is_required: true
      - type: form_field
        template: form_field
        input_type: email
        name: email
        label: EMAIL
        default_value: Your email address
        is_required: true
      - type: form_field
        template: form_field
        input_type: textarea
        name: message
        label: MESSAGE
        default_value: Your message
      - type: form_field
        template: form_field
        input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
template: advanced
---
