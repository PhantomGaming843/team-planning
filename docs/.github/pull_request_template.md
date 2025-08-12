name: Task
description: Plan a piece of work
title: "[Task] <short title>"
labels: ["todo"]
body:
  - type: textarea
    id: goal
    attributes:
      label: Goal / Outcome
      description: What should be true when this is done?
      placeholder: Clear, testable outcome
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Acceptance Criteria
      description: Bullet list of criteria
      placeholder: "- [ ] criteria 1\n- [ ] criteria 2"
  - type: input
    id: sprint
    attributes:
      label: Target Sprint
      placeholder: e.g., 2025-08 Sprint 2
  - type: dropdown
    id: priority
    attributes:
      label: Priority
      options:
        - High
        - Medium
        - Low
