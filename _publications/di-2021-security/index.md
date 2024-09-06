---
layout: single_publication
title: Security assessment of common open source MQTT brokers and clients
slug: security-assessment-of-common-open-source-mqtt-brokers-and-clients

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Edoardo Di Paolo
- Enrico Bassetti
- Angelo Spognardi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-09-06T07:33:03.617695Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: 'ITASEC 2021'
publication_short: ''

doi: ''

abstract: 'Security and dependability of devices are paramount for the IoT ecosystem. Message Queuing Telemetry Transport protocol (MQTT) is the de facto standard and the most common alternative for those limited devices that cannot leverage HTTP. However, the MQTT protocol was designed with no security concern since initially designed for private networks of the oil and gas industry. Since MQTT is widely used for real applications, it is under the lens of the security community, also considering the widespread attacks targeting IoT devices. Following this direction research, in this paper we present an empirical security evaluation of several widespread implementations of MQTT system components, namely five broker libraries and three client libraries. While the results of our research do not capture very critical flaws, there are several scenarios where some libraries do not fully adhere to the standard and leave some margins that could be maliciously exploited and potentially cause system inconsistencies.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  icon: 'bi bi-filetype-pdf'
  value: 'PDF'
  url: 'https://ceur-ws.org/Vol-2940/paper40.pdf'
---