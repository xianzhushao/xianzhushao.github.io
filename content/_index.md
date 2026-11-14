---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      background:
        color: '#ffffff'
        image:
          filename: ''

  - block: markdown
    id: news
    content:
      title: '📰 News'
      subtitle: ''
      text: |-
        - **[2026.08]** Started my Ph.D. in Computer Science and Engineering at UT Arlington, joining the [MIND Lab](https://ranger.uta.edu/~zhu) under Prof. Dajiang Zhu.
        - **[2025.12]** One paper (co-first author) accepted by *Journal of Forecasting* (JCR Q1).
        - **[2024.12]** One paper accepted by *Resources Policy* (JCR Q1).
        - **[2024.06]** Joined the Tencent & Canway Joint R&D Team as an AI Algorithm Engineer.
        - **[2023.06]** Received my B.Sc. in Mathematics and Applied Mathematics from Tianjin University of Commerce.
        - **[2023.04]** Joined Multisim as an AI Algorithm Engineer.
    design:
      columns: '1'

  # ---- My Research (hidden until content is ready) ----
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       TODO
  #   design:
  #     columns: '1'

  # ---- Featured Publications (hidden for now) ----
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2

  - block: collection
    id: papers
    content:
      title: '📝 Publications'
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: markdown
    id: service
    content:
      title: '🔍 Academic Service'
      text: |-
        **Journal Reviewer**
        - *Engineering Applications of Artificial Intelligence* (EAAI)
        - *Journal of Forecasting*
        - *Transportation Letters*

        **Conference Reviewer**
        - IEEE International Symposium on Biomedical Imaging (ISBI) 2027
    design:
      columns: '1'

  # ---- Visitor map (MapMyVisitors, stats: https://mapmyvisitors.com/web/1c9hh) ----
  - block: markdown
    id: visitors
    content:
      title: ''
      text: |-
        <div style="width:320px;max-width:100%;margin:0 auto;">
        <script type="text/javascript" id="mapmyvisitors" src="https://mapmyvisitors.com/map.js?d=68enhMm_cZFGWA_M22rTaeRcBoPwsw9FQcHCI0UBSTs&cl=ffffff&w=320"></script>
        </div>
    design:
      columns: '1'

  # ---- Talks (hidden for now) ----
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
---
