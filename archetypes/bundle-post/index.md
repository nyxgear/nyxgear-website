---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
hidemeta: false
comments: false
canonicalURL: "https://canonical.url/to/page"
hideSummary: false

# showToc: true
# TocOpen: true
# UseHugoToc: true

cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
---

