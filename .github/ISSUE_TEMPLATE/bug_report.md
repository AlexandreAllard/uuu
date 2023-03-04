---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

name: Bug Report
description: File a reproducible bug or regression.
body:
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Please describe the bug.
    validations:
      required: true
  - type: textarea
    id: repro
    attributes:
      label: Reproduction steps
      description: How do you trigger this bug? Please walk us through it step by step.
      value: |
        1.
        2.
        3.
    validations:
      required: true
  - type: textarea
    id: code
    attributes:
      label: Code
      value: |
        ```js
        // write your code
        ```
    validations:
      required: true
  - type: dropdown
    id: device
    attributes:
      label: Device
      multiple: true
      options:
        - Desktop
        - Mobile
        - Headset
  - type: dropdown
    id: browser
    attributes:
      label: Browser
      multiple: true
      options:
        - Chrome
        - Firefox
        - Safari
        - Edge
  - type: dropdown
    id: os
    attributes:
      label: OS
      multiple: true
      options:
        - Windows
        - MacOS
        - Linux
        - Android
        - iOS
