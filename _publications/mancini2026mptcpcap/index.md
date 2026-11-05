---
layout: single_publication
title: 'MPTCPcap: A Practical Framework for Security Testing of Multipath TCP'
slug: mptcpcap-a-practical-framework-for-security-testing-of-multipath-tcp
authors:
- Riccardo Mancini
- Federica Bianchi
- Angelo Spognardi
author_notes: []
date: '2026-02-09'
publishDate: '2026-11-03T15:28:00Z'
publication_types: 'paper_conference'
publication: 'Proceedings of 2nd Joint National Conference on Cybersecurity (ITASEC & SERICS 2026)'
publication_short: 'ITASEC/SERICS 2026'
doi: ''
abstract: 'Multipath TCP (MPTCP) improves reliability and performance by enabling multiple network paths for a single connection, but its security remains a concern. In this paper we present MPTCPcap, a real-time and reusable analysis tool for monitoring MPTCP connections and simulating attacks. The tool tracks subflows, endpoints, and keys in real time and supports packet injection, modification, and dropping, enabling emulation of off-path, partial on-path, and full on-path adversaries. Using MPTCPcap, we reassess well-known MPTCPv0 attacks against the Linux MPTCPv1 implementation and identify two previously undocumented vulnerabilities: (i) an off-path attack that closes subflows in Linux’s MPTCP implementation, and (ii) a protocol-level weakness allowing an attacker with connection keys to prevent the creation of new subflows. Our results highlight how adversarial testing of MPTCP implementations can expose residual security issues and provide a practical basis for future security analysis and mitigation efforts.'
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
  url: 'https://ceur-ws.org/Vol-4198/paper43.pdf'
- name: GitHub
  icon: 'bi bi-github'
  value: 'Code'
  url: 'https://github.com/netsecuritylab/mqtt'
---
