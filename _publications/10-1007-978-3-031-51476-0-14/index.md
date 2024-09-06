---
layout: single_publication
title: A New Model for Testing IPv6 Fragment Handling
slug: a-new-model-for-testing-ipv6-fragment-handling

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

date: '2023-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-09-06T07:33:03.634793Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: 'Computer Security - ESORICS 2023'
publication_short: ''

doi: ''

abstract: Since the origins of the Internet, various vulnerabilities exploiting the
  IP fragmentation process have plagued IPv4 protocol, many leading to a wide range
  of attacks. IPv6 modified the handling of fragmentations and introduced a specific
  extension header, not solving the related problems, as proved by extensive literature.
  One of the primary sources of problems has been the overlapping fragments, which
  result in unexpected or malicious packets when reassembled. To overcome the problem
  related to fragmentation, the authors of RFC 5722 decided that IPv6 hosts MUST silently
  drop overlapping fragments.

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
  value: "PDF"
  icon: 'bi bi-filetype-pdf'
  url: https://arxiv.org/pdf/2309.03525
- name: GitHub
  icon: 'bi bi-github'
  value: 'Code'
  url: 'https://github.com/netsecuritylab/ipv6-fragmentation'
---