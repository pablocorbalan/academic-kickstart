---
title: "Chorus: UWB Concurrent Transmissions for GPS-like Passive Localization of Countless Targets"
authors:
- admin
- Gian Pietro Picco
- Sameera Palipana
date: "2019-04-01T00:00:00Z"
doi: "10.1145/3302506.3310395"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 18th International Conference on Information Processing in Sensor Networks (IPSN), Montreal (Canada), April 2019*
publication_short: In *IPSN'19*

abstract: We propose Chorus, a new ultra-wideband (UWB) localization scheme in which the target device computes the time difference of arrival (TDOA) of signals sent concurrently by localization anchors in known positions. This scheme, similar to GPS, is the opposite of existing TDOA schemes for UWB, where the target transmits the signal and anchors compute the time difference. This reversed perspective enables several advantages in Chorus, including support for countless targets.<br>The cornerstone and novelty of Chorus is the use of concurrent transmissions from anchors; distance information is acquired at the receiver based on the channel impulse response (CIR) resulting from the fused signals. We contribute i) an analytical model enabling a priori estimation of the CIR resulting from the superposition of concurrent signals ii) techniques to accurately extract the time-of- flight information necessary for localization from the measured CIR, and iii) real-world experiments that validate the model as well as assess the practical feasibility and performance of Chorus.<br>Experiments with the DW1000 UWB chip show that Chorus achieves sub-meter positioning accuracy. However, our model shows that performance is limited by idiosyncrasies of the DW1000 that, if removed in next-generation UWB hardware, could unlock an order of magnitude improvement in accuracy.

# Summary. An optional shortened abstract.
summary: ' '

tags:
- Ultra-wideband
- Concurrent Transmissions
- TDOA Localization
featured: true

links:
url_pdf: 'files/papers/chorus-ipsn19.pdf'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
