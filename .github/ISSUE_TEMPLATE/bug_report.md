---
name: "🐞 Bug Report"
about: "Create a detailed report to help us improve ComicFlow."
title: "[BUG] - Brief description of the issue"
labels: ["bug", "needs-triage"]
assignees:
  - chirag127
body:
  - type: markdown
    attributes:
      value: |
        **Thank you for contributing to ComicFlow!**

        Please fill out this form with as much detail as possible. High-quality bug reports help us resolve issues faster.

  - type: textarea
    id: bug-description
    attributes:
      label: "Bug Description"
      description: "Provide a clear and concise summary of the bug."
      placeholder: "When I try to dub a comic from [URL], the audio narration stops after the first panel."
    validations:
      required: true

  - type: textarea
    id: steps-to-reproduce
    attributes:
      label: "Steps to Reproduce"
      description: "Describe the exact steps to reproduce the problem. This is critical."
      value: |
        1. Go to '...'
        2. Click on '....'
        3. Scroll down to '....'
        4. Observe the error
    validations:
      required: true

  - type: textarea
    id: expected-behavior
    attributes:
      label: "Expected Behavior"
      description: "What did you expect to happen?"
      placeholder: "The narration should continue smoothly for all panels on the page."
    validations:
      required: true

  - type: textarea
    id: screenshots
    attributes:
      label: "Screenshots & Recordings"
      description: "If applicable, add screenshots, GIFs, or video recordings to help explain the problem. You can drag and drop files here."
    validations:
      required: false

  - type: input
    id: os
    attributes:
      label: "Operating System"
      description: "What operating system are you using?"
      placeholder: "e.g., Windows 11, macOS Sonoma 14.2"
    validations:
      required: true

  - type: input
    id: browser
    attributes:
      label: "Browser"
      description: "What browser and version are you using?"
      placeholder: "e.g., Chrome 120, Firefox 119"
    validations:
      required: true

  - type: textarea
    id: additional-context
    attributes:
      label: "Additional Context & Logs"
      description: "Add any other context about the problem here. If you see any errors in your browser's developer console (F12), please paste them here."
      placeholder: "This seems to happen only with comics that use non-standard fonts..."

  - type: checkboxes
    id: issue-checklist
    attributes:
      label: "Verification Checklist"
      description: "Please verify the following before submitting."
      options:
        - label: "I have searched the existing [issues](https://github.com/chirag127/ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App/issues) to confirm this bug has not been reported before."
          required: true
        - label: "I have confirmed this issue is reproducible with the latest version of ComicFlow."
          required: true
        - label: "I have provided all the necessary information for the team to investigate."
          required: true
---
