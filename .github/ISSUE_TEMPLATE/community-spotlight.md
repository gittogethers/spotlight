name: 🌟 Community Spotlight Submission
description: Showcase your open-source project for the GitTogethers Community Spotlight!
title: Title Would Be Updated By Automation
labels: Community Spotlight, Submission
body:
  - type: dropdown
    id: event
    attributes:
      label: Which GitTogether would you like to present at? *
      options:
        - Bengaluru
        - Delhi NCR
        - Hyderabad
        - Mumbai
        - Other
    validations:
      required: true

  - type: input
    id: project_title
    attributes:
      label: Project Title *
    validations:
      required: true

  - type: textarea
    id: project_description
    attributes:
      label: Project Description *
    validations:
      required: true

  - type: input
    id: repo_url
    attributes:
      label: GitHub Repository URL *
      placeholder: https://github.com/username/repository
    validations:
      required: true

  - type: input
    id: project_link
    attributes:
      label: Live Project Link (for end-users) *
      placeholder: https://example.com
    validations:
      required: true

  - type: input
    id: full_name
    attributes:
      label: Full Name *
    validations:
      required: true

  - type: input
    id: role
    attributes:
      label: Role/Designation and Company Name *
    validations:
      required: true

  - type: input
    id: city
    attributes:
      label: City *
    validations:
      required: true

  - type: dropdown
    id: country
    attributes:
      label: Country *
      options:
        - India
        - Brazil
        - Colombia
        - Other
    validations:
      required: true

  - type: input
    id: linkedin
    attributes:
      label: LinkedIn Profile Link
      placeholder: https://linkedin.com/in/username

  - type: input
    id: twitter
    attributes:
      label: Twitter/X Username
      placeholder: @username

  - type: dropdown
    id: social_media_tagging
    attributes:
      label: Will you be okay with us tagging you on social media? *
      options:
        - Yes
        - No
    validations:
      required: true