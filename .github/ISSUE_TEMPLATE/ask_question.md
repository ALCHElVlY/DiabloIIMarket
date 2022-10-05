name: Submit A Question
description: If you have a general question regarding a feature or function on the app
title: "[Question]: <title>"
labels: [question]
assignees: ''
  
body:
- type: dropdown
  id: download
  attributes:
    label: How did you download the software?
    options:
      - Homebrew
      - MacPorts
      - apt-get
      - Built from source
  validations:
    required: true
