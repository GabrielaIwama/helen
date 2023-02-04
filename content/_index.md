---
# Leave the homepage title empty to use the site title
title: Helen Iwama
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Fazendo seus direitos serem respeitados desde XXXX
      image:
        filename: hero-academic.png
    text: |-
        Advogada Cível, ..., ...
        [Coisas que vc pode fazer]
    design:
      background:
        gradient_end: '#85A392'
        gradient_start: '#738C7E'
        text_color_light: true
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    id: atuacao
    content:
      title: Áreas de Atuação
      items:
        - name: Cível
          description: Ações de inventários, divórcios, guardas, interdições.
          icon: r-project
          icon_pack: fab
        - name: Trabalhista
          description: Assessoria e ações preventiva e contenciosa.
          icon: chart-line
          icon_pack: fas
        - name: Imobiliário
          description: |2-
            Assessoria imobiliária, análise para segurança em compra e aluguel de imóveis,
            ações de despejo, reintegração de posse, dissolução de condomínio.
          icon: camera-retro
          icon_pack: fas
  - block: experience
    content:
      title: Experiência Profissional
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
      - title: Especialização em Direito Imobiliário
        company: Pontifícia Universidade Católica de São Paulo
        company_logo: org-puc
        location: São Paulo, SP
        #date_start: '20-01-01'
        date_end: '2014-12-31'
      - title: Bacharel em Direito
        company: Universidade Cidade de São Paulo
        company_logo: org-d
        location: São Paulo, SP
        #date_start: '20-01-01'
        date_end: '2008-12-31'
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contato
      subtitle:
      text: Entre em contato para consultas de honorários
      # Contact (add or remove contact options as necessary)
      email: heleniwama@gmail.com
      phone: (11) 97542-5427
    design:
      columns: '1'
---
