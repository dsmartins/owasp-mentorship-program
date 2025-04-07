name: Mentor Application
description: Apply to be a mentor in the OWASP Mentorship Program
body:
  - type: input
    attributes:
      label: Name & GitHub handle
  - type: input
    attributes:
      label: Areas of expertise
  - type: textarea
    attributes:
      label: Past mentoring or OWASP contribution experience
  - type: checkboxes
    attributes:
      label: Preferred track(s)
      options:
        - label: OWASP ZAP
        - label: OWASP ASVS / MASVS
        - label: Threat Modeling
        - label: Secure Coding
        - label: Community Leadership
