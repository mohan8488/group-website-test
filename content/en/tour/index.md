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
            filename: tour.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Fast DDM 🔬
        content: 'FastDDM is a robust Python package we engineered to streamline the analysis of Differential Dynamic Microscopy experiments. Dive into the core of FastDDM and discover how its integration with C++ and CUDA elevates performance, offering rapid and precise execution on both CPU and GPU. For more information contact [E. Lattuada](https://mohan8488.github.io/group-website-test/author/enrico-lattuada/).'

        align: left
        background:
          image:
            filename: DDM-2.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Nonlinear dynamics of soft materials 🧈
        #We study the dynamics of soft materials like pastes, emulsions and gels, undergoing shear flow induced by a controlled mechanical deformation. We primarily investige “yielding”, a transition from a solid-like to a liquid-like mechanical behavior of soft materials.
        content: 'Coupling rheometry with microscopy, we study the dynamics of soft materials like pastes, emulsions and gels, undergoing shear flow. This method allows us to measure the macroscopic mechanical properties of the material and simultaneously track embedded microparticles to assess the localized shear-induced diffusion. We design and prototype and/or improve custom-made instruments, develop codes (LabVIEW, MatLab) and perform image Processing. For more information contact [N. Kalafatakis](https://mohan8488.github.io/group-website-test/author/nikolaos-kalafatakis/).'
        align: left
        background:
          image:
            filename: shear_cell.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#444'
      - title: Structure & dynamics in Cellular Monolayers 🧫
        content: 'Through particle image velocimetry (PIV) we can probe dynamical changes in cellular monolayers, their velocity correlation lengths and directional alignments and orderedness. A different perspective on cellular dynamics comes from following the trajectories of single cells within a monolayer, which provides the general quantity mean square displacement (MSD) and its scaling behaviour over time, opening a porthole into the dynamics of a cellular monolayer as it ages. For more information on this project contact **[Fabian](https://mohan8488.github.io/group-website-test/author/fabian-krautgasser/)**'
        align: left
        background:
          image:
            filename: PIV.jpg
            filters:
              brightness: 1
          position: center
          color: '#333'
      - title: Mechanobiology 🧬
        content: 'Mechanobiology delves into the mechanisms by which cells produce forces essential for their functions and tissue integrity, encompassing the conversion of mechanical stimuli into biochemical signals across different scales. Using rheo-microscopy we investigate the role of cell-cell and cell-extracellular matrix (ECM) interactions in the overall rheological response of tissues under both physiological and pathological (tumor) conditions. For more information contact [J. Di Franco](https://mohan8488.github.io/group-website-test/author/jasmin-di-franco/).'
        align: left
        background:
          image:
            filename: biolab-5.jpg
            filters:
              brightness: 0.9
          position: bottom
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
