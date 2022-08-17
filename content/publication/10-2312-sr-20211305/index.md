---
title: A Compact Representation for Fluorescent Spectral Data
subtitle: ''
summary: 'Eurographics Symposium on Rendering (EGSR)'
authors:
  - Qingqin Hua
  - Alban Fichet
  - Alexander Wilkie
doi: 10.2312/sr.20211305
publication: "*Eurographics Symposium on Rendering - DL-only Track*"
abstract: ""
draft: false
featured: false
tags: []
categories: []
date: '2021-06-01'
lastmod: 2022-08-17T22:51:25+02:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021'
publication_types:
- '1'
abstract: 'We propose a technique to efficiently importance sample and store fluorescent spectral data. Fluorescence behaviour is properly
represented as a re-radiation matrix: for a given input wavelength, this matrix indicates how much energy is re-emitted at all
other wavelengths. However, such a 2D representation has a significant memory footprint, especially when a scene contains a
high number of fluorescent objects, or fluorescent textures. We propose to use Gaussian Mixture Domain to model re-radiation,
which allows us to significantly reduce the memory footprint. Instead of storing the full matrix, we work with a set of Gaussian
parameters that also allow direct importance sampling. When accuracy is a concern, one can still use the re-radiation matrix
data, and just benefit from importance sampling provided by the Gaussian Mixture. Our method is useful when numerous
fluorescent materials are present in a scene, an in particular for textures with fluorescent components.
'
publication: '*Eurographics Symposium on Rendering - DL-only Track*'
url_pdf: "https://diglib.eg.org/bitstream/handle/10.2312/sr20211305/225-234.pdf?sequence=1&isAllowed=y"
url_code: "https://gitlab.com/huaq_/compact-representation-fluorescence"
url_slides: "https://github.com/qingqhua/academic/raw/main/content/publication/10-2312-sr-20211305/EGSR2021.pdf"
---
