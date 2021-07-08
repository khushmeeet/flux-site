---
template: docs-detail
title: Flux Pages
---

## Flux Pages

Flux page defines a webpage, whose content is written in markdown. It is mostly used for blog posts. Every flux page is defined inside a folder. Folder name can be anything, but is preferred to name after the page title. Each page folder has a markdown file and assets(images or any other file, that is specific to that post).

Here is a sample flux page directory:

```bash
.
└── flux-posts
        ├── General_flux_diagram.svg.png
        └── flux-posts.md
```

#### Frontmatter

Every markdown file has to contain frontmatter section at the top of the file to define content metadata, enclosed between two ```---``` . There are two fields that are mandatory in frontmatter, ```title``` and ```template```. If these two fields are not present, ```flux build``` command will fail. 

You can add other fields like ```date```, ```category``` etc, depending on the requirement. Lists and other structures can also be added to the frontmatter, as it is essentially a YAML structure.

Here is a sample frontmatter:

```yaml
---
template: post
title: How to run upspin on GCE
shortie: Tutorial on how to setup upspinserver on Google Compute Engine
categories: data
tags:
  Upspin
  File sharing
---
```
