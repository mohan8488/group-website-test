---
title: Tour
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: Office.jpg
            filters:
              brightness: 0.5
          position: right
          color: '#666'
      - title: Fast DDM 🔬
        content: FastDDM is a robust Python package we engineered to streamline the analysis of Differential Dynamic Microscopy experiments. Dive into the core of FastDDM and discover how its integration with C++ and CUDA elevates performance, offering rapid and precise execution on both CPU and GPU.

        align: left
        background:
          image:
            filename: DDM-2.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Nonlinear dynamics of soft materials 🧈
        content: 'We study the dynamics of soft materials like pastes, emulsions and gels, undergoing shear flow induced by a controlled mechanical deformation. Coupling rheometry with microscopy allows us to measure the macroscopic mechanical properties of the material and at the same time track embedded microparticles to assess the localized shear-induced diffusion. we primarily investige “yielding”, a transition from a solid-like to a liquid-like mechanical behavior of soft materials. The project involves design and prototyping and/or improvement of custom-made instruments, as well as coding (LabVIEW, MatLab) and Image Processing.'
        align: left
        background:
          image:
            filename: shear_cell_edit.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#444'
      - title: Particle Image Velocimetry (PIV) 🔆
        content: 'Short description...'
        align: left
        background:
          image:
            filename: PIV.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
      - title: Biolab 🦠
        content: 'Opened in 2023!'
        align: right
        background:
          image:
            filename: biolab.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#222'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---
