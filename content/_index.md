---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Write Docs Fast, Focus on Your Content
      text: The easy, no-code technical documentation solution your users will love 🎉
      primary_action:
        text: Get Started
        url: https://hugoblox.com/templates/details/docs/
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: /docs/
      announcement:
        text: "Announcing the release of version 2."
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: ""
          filters:
            brightness: 0.5
  - block: features
    id: features
    content:
      title: Tópicos
      text: Tópicos de pesquisa e desenvolvimento.
      items:
        - name: Otimização
          icon: magnifying-glass
          description: Otimização para redes neurais, otimização multi-objetivo.
        - name: Aprendizado Profundo
          icon: bolt
          description: Arquiteturas, funções objetivo, regularização.
        - name: Explicabilidade
          icon: sparkles
          description: Interpretação de redes profundas, explicações contrafactuais.
        - name: Fairness
          icon: code-bracket
          description: Algoritmos, métricas.
        - name: Teoria do Aprendizado
          icon: star
          description: Generalização, convergência.
        - name: ...e muito mais.
          icon: rectangle-group
          description: 
---
