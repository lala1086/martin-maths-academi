name: Feature Request
description: Suggest a new feature or improvement
title: "[FEATURE] "
labels: ["enhancement"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for suggesting a feature! ✨
  - type: textarea
    attributes:
      label: Feature description
      description: Describe the feature you'd like to see
      placeholder: I would like to...
    validations:
      required: true
  - type: textarea
    attributes:
      label: Why is this needed?
      description: Explain why this feature would be useful
      placeholder: This would help because...
    validations:
      required: true
  - type: textarea
    attributes:
      label: Proposed implementation
      description: How should this feature work? Any ideas on implementation?
      placeholder: The feature could work by...
    validations:
      required: false
  - type: textarea
    attributes:
      label: Alternative solutions
      description: Are there any alternative solutions?
    validations:
      required: false
