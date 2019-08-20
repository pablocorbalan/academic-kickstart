---
title: "Tales from the C130 Horror Room: A Wireless Sensor Network Story in a Data Center"
authors:
- Ramona Marfievici
- admin
- David Rojas
- Alan McGibney
- Susan Rea
- Dirk Pesch
date: "2017-11-05T00:00:00Z"
doi: "10.1145/3143337.3143343"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: " In Proceedings of the 1st ACM International Workshop on the Engineering of Reliable, Robust, and Secure Embedded Wireless Sensing Systems (FAILSAFE), Delft (The Netherlands), November 2017."
publication_short: "FAILSAFE'17"

abstract: An important aspect of the management and control of modern data centers is cooling and energy optimization. Airflow and tem- perature measurements are key components for modeling and pre- dicting environmental changes and cooling demands. For this, a wireless sensor network (WSN) can facilitate the sensor deploy- ment and data collection in a changing environment. However, the challenging characteristics of these scenarios, e.g., temperature fluctuations, noise, and large amounts of metal surfaces and wiring, make it difficult to predict network behavior and therefore network planning and deployment. In this paper we report a 17-month long deployment of 30 wireless sensor nodes in a small data center room, where temperature, humidity and airflow were collected, along with RSSI, LQI, and battery voltage. After an initial unreliable period, a connectivity assessment performed on the network revealed a high noise floor in some of the nodes, which together with a default low CCA threshold triggered no packet transmissions, yielding a low PDR for those nodes. Increasing the CCA setting and relocating the sink allowed the network to achieve a reliability of 99.2% for the last eight months of the deployment, therefore complying with the project requirements. This highlights the necessity of using proper tools and dependable protocols, and defining design methodologies for managing and deploying WSNs in real-world environments.

# Summary. An optional shortened abstract.
summary: ' '

tags:
- Wireless Sensor Networks
featured: true

links:
url_pdf: 'files/papers/tales-c130-failsafe17.pdf'
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
