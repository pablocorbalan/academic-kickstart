---
title: "Concurrent Ranging in Ultra-wideband Radios: Experimental Evidence, Challenges, and Opportunities"
authors:
- admin
- Gian Pietro Picco
date: "2018-02-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the 15th International Conference on Embedded Wireless Systems and Networks (EWSN), Madrid (Spain), February 2018.
publication_short: "EWSN'18"

abstract: This paper investigates the feasibility of a novel primitive for concurrent ranging in ultra-wideband (UWB) radios. Conventional ranging protocols schedule the packet transmissions used to estimate distance to be separate in time. In contrast, our concurrent ranging primitive relies on the overlapping of these transmissions; when a ranging request is issued by an initiator node, all nodes in range immediately reply back. These concurrent signals are “fused” in the communication channel, whose channel impulse response (CIR) is made available by the DecaWave DW1000 transceiver we use in this paper. Combined with the fact that UWB transmissions rely on very short (<2 ns) pulses, the CIR enables the initiator to determine the precise timing of the individual signals, and therefore estimate accurately the distance of the corresponding responders.<br>Concurrent ranging removes the need for scheduling, and is faster and less energy-hungry than traditional scheduled schemes. We report empirical evidence that our idea is feasible, and use it as a basis to elicit the challenges and limitations of concurrent ranging, the opportunities for significant improvements w.r.t. the current state of the art, and the preliminary techniques that can be used to achieve them.

# Summary. An optional shortened abstract.
summary: ' '

tags:
- Ultra-wideband
- Concurrent Transmissions
- Ranging
featured: true

links:
- name: Best Paper Award
  url: http://ewsn.org
url_pdf: 'files/papers/crng-ewsn18.pdf'
url_code: ''
url_slides: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
This paper received the *Best Paper Award* at EWSN'18.
{{% /alert %}}