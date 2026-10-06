---
title: Francisco Javier Labbé Opazo
date: 2026-10-06
type: landing

# Los datos del profesor están en data/authors/francisco-labbe.yaml
sections:
  - block: resume-biography-3
    content:
      username: francisco-labbe
      text: ''
      headings:
        about: 'Perfil'
        education: 'Formación'
        interests: 'Áreas de interés'
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  # Publicaciones: content/publications/ con `authors: [francisco-labbe]`
  - block: collection
    id: publicaciones
    content:
      title: Publicaciones
      filters:
        folders:
          - publications
        author: francisco-labbe
      count: 0
      order: desc
    design:
      view: citation
---
