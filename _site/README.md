# Run locally

`jekyll serve`

# Build pagefind

`npx pagefind --site .`


# How to add a publication
First of all install this python (IIRC it needs python > 3.10) library: https://github.com/GetRD/academic-file-converter

Add the publication to the `netseclab.bib ` file.

Then run the command:

`academic import netseclab.bib ./_publications --compact`.

Now, you can edit your new publication .md file (inside the folder _publications/XXXXXXX/index.md).

It should be something like that:

```
---
layout: single_publication
title: Paper title
authors:
- Author 1
- Author 2
- ....
date: '2024-01-01'
publishDate: '2024-01-01T19:21:49.395758Z'
publication_types:
- paper_conference
publication: "CONFERENCE NAME"
links:
- name: URL
  icon: 'bi bi-filetype-pdf'
  value: 'PDF'
  url: URL_TO_PDF
abstract: Paper abstract.
---
```

The publication_types options are: "paper_conference", "paper_journal" and "paper_preprint".

