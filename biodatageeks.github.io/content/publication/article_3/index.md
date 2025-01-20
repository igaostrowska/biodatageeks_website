---
title: "Cloud-native distributed genomic pileup operations"
authors:
- Tomasz Gambin
- Marek Wiewiórka
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-01-01T00:00:00Z"
doi: https://doi.org/10.1093/bioinformatics/btac804

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: |
  Motivation: 
  Pileup analysis is a building block of many bioinformatics pipelines, including variant calling and genotyping. This step tends to become a bottleneck of the entire assay since the straightforward pileup implementations involve processing of all base calls from all alignments sequentially. On the other hand, a distributed version of the algorithm faces the intrinsic challenge of splitting reads-oriented file formats into self-contained partitions to avoid costly data exchange between computational nodes.

  Results: 
  Here, we present a scalable, distributed and efficient implementation of a pileup algorithm that is suitable for deploying in cloud computing environments. In particular, we implemented: (i) our custom data-partitioning algorithm optimized to work with the alignment reads, (ii) a novel and unique approach to process alignment events from sequencing reads using the MD tags, (iii) the source code micro-optimizations for recurrent operations, and (iv) a modular structure of the algorithm. We have proven that our novel approach consistently and significantly outperforms other state-of-the-art distributed tools in terms of execution time (up to 6.5× faster) and memory usage (up to 2× less), resulting in a substantial cloud cost reduction. SeQuiLa is a cloud-native solution that can be easily deployed using any managed Kubernetes and Hadoop services available in public clouds, like Microsoft Azure Cloud, Google Cloud Platform, or Amazon Web Services. Together with the already implemented distributed range join and coverage calculations, our package provides end-users with a unified SQL interface for convenient analyses of population-scale genomic data in an interactive way.





# tags:
# - Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://watermark.silverchair.com/btac804.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAA3EwggNtBgkqhkiG9w0BBwagggNeMIIDWgIBADCCA1MGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMRiacW6f34IUgYH46AgEQgIIDJJQjztaicGda7HbfW_59HxZ4VppausGML4QLckxDlyM0taZm8_NumjjuEm8EJ2ggq5V6CSRSi4Kti1ZNuqjiFZ4ngEiYOKxQFt72WsCpfxwb1ZbzMD6_r0v0Jy_vaswZ55o4JD8x6QNBRCrj5BDNMYhrzoeo0BogsqKHPJgg3nqzGKbqnL_fp7Ws5JOdtq10C0RMHqufNZciyijPEMM_YH-pEwNzzQzAh6KfO_XiddS-3NCIuc0akDVUq5E3eCXbFs1CyVEN092Ag_aKEC10EKKjINPb6q6QFFVZt92PJH7AIO4wLB2Eh2BS9PNoA2Nq0S6ib3evvwAhcs2uJrBoM2hCx_gwQkGVq9Yn8h0hk4yVuXCIXmdmsx9sqVRmLFZKuGIEemY5O8sqYN6YORZwaFeEU_8McUyFhd_b7M5cUVG9Q9dymX2tHTQzoH6wfI-07WAANkGe6Qiqi9ScF5K7oV5FO9s34aSy6aZ3YxAHMXHxo5QSSNy53AJJuecOqMx_0IOxz61aCrD0Xnctz934yCo4zchI4DYKO9wH5fYe707DUOmbkcKu42GDjsbk7gxEaYTevVih2vozjkH-7XfsdiWzfS-kGhk18aqjpZ790r9UWk-wF9NwtQpGtK4ykoCftA0s17BJRRUcfsjHQiexzPsU4XRp4PVy5KhG1CuomYaR1lORvPQe9s-fuM9HpEptetQIgLQgl8CZWG0Q68n7RGQu3BvVseDl8QJ-AA0myiVpiNLH_bmuiSo7x5HTf6fK3Unc8-jd30BlmDxZlby0i2a5Av2UHvLcBmjOaijRU5YI-vpBbyVLMiQMH5nrNSQIfE39RFlOnwAMykX85nEdXC6Dy-fgnpQGVOfbgWnxWC4r_ReBbe9dmPyA7sGNFnoUgNsohICyDEnUhn4ddE7s4mGv3obu85kARj9Dxx1KxNqTE_9svIxnJl6ffTbKlwLqU-pWYzRjY_rSYhqqz4Vw7o_KRJYmwLkEYDN4jRYJVj3LiENu89h59mg6oyk5Xrpz4zmM1wssgE5Q27IfXbXazaX8uRvDDYFm3TcBPoECj-3y38RQ-w
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---




