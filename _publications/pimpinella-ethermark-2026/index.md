---
layout: single_publication
title: 'EtherMark: A novel architecture for mobile-traffic dataset creation with perfect labeling'
slug: ethermark-a-novel-architecture-for-mobile-traffic-dataset-creation-with-perfect-labeling


authors:
- Giovanni Pimpinella
- Angelo Spognardi
author_notes: []
date: '2026-06-16'
publishDate: '2026-11-03T15:28:00Z'
publication_types: 'paper_conference'
publication: 'Proceedings of the 27th IEEE International Symposium on a World of Wireless, Mobile and Multimedia Networks (WOWMOM)'
publication_short: 'WOWMOM 2026'
doi: 'https://doi.org/10.1109/WoWMoM69805.2026.00039'
abstract: 'Most approaches to network traffic analysis require reliable and accurately labeled datasets, particularly when they embrace machine learning techniques. However, the vast majority of the released datasets rely on collection processes with several weaknesses, like undisclosed details for reproducibility, questionable design choices, scalability issues, or imperfect labeling performance. This paper proposes a novel methodology for creating accurately labeled datasets for analyzing encrypted Android traffic. Our methodology relies on a flexible architecture and aims to overcome all the issues of previous approaches by exploiting a loadable kernel module. Leveraging the netfilter infrastructure, the generating device accurately embeds a label into each packet sent, without requiring any storage or logging, while a local collecting device removes the labels and forwards the packets to the intended destination, also linking any response packets to the related application. By reading the labels directly from the kernel, EtherMark is guaranteed by design to have perfect label accuracy. Combined with the minimal overhead introduced, our methodology outperforms all other approaches in the literature. We release the implementation code of our module as free software, along with the dataset used for tests.'
summary: ''
tags: []
featured: false
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
links:
- name: URL
  value: "PDF"
  icon: 'bi bi-filetype-pdf'
  url: 'https://doi.org/10.1109/WoWMoM69805.2026.00039'
- name: GitHub
  icon: 'bi bi-github'
  value: 'Code'
  url: 'https://github.com/netsecuritylab/EtherMark'
---
