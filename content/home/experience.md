---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Fellow
    company: Oden Institue for Computational Engineering & Sciences
    company_url: 'https://oden.utexas.edu/'
    company_logo: Stacked-Fullcolor
    location: Mississippi (Remote)
    date_start: '2022-10-01'
    date_end: ''
    description: |2-
        Projects include:

        * Development of compound flood simulation capabilities within Adaptive Hydraulics (AdH)
        * Reduced order modeling for coastal engineering applications
        * Development of physics-based operator learning framework for environmental flows

  - title: ORISE Postdoctoral Fellow
    company: U.S. Army Engineer Research & Development Center (ERDC)
    company_url: 'https://www.erdc.usace.army.mil/'
    company_logo: ERDC
    location: Mississippi
    date_start: '2017-09-01'
    date_end: '2022-08-31'
    description: |2-
        Projects include:

        * Development of reduced order model (ROM) for shallow water flows
        * Data-driven ROMs for computational fluid dynamics problems
        * Machine learning (ML)-based ROM for advection-dominated flows
        * Python-based, open source package for ROM development

design:
  columns: '2'
---
