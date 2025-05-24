---
name: feature_request
about: Suggest a new feature or improvement for the app.
title: ''
labels: ''
assignees: ''

---

name: ✨ Feature Request
description: Suggest a new feature or improvement
title: "[Feature] "
labels: ["enhancement"]
body:
  - type: textarea
    attributes:
      label: Feature description
      description: Describe the feature or enhancement you'd like to see.
      placeholder: Add a "What to discard?" feature, support dark mode, etc.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Purpose / Motivation
      description: Why is this feature useful? What problem does it solve?
      placeholder: Helps users practice real game decisions, improves usability, etc.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Additional context
      description: Include any other details, references, or screenshots.
      placeholder: e.g., Related services, mockups, relevant links
    validations:
      required: false
