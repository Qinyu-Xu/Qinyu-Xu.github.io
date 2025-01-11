---
title: "OPENTE: OPEN-STRUCTURE TABLE EXTRACTION FROM TEXT"
authors:
- Haoyu Dong
- Mengkang Hu
- admin
- Haochen Wang
- Yue Hu
date: "2024-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "This paper presents an Open-Structure Table Extraction(OpenTE) task, which aims to extract a table with intrinsic semantic, calculational, and hierarchical structure from unstructured text. We devise a novel Identification-Extraction-Grounding (IEG) framework for language models (LMs) comprising three chaining steps: (1) identifying semantic and calculational relationships among columns, (2) extracting structured data from unstructured text, and (3) aligning extracted data with the source text and the table structure with a separate discrete grounding model. Experiment results suggest that OpenTE presents a significant challenge for state-of-the-art LMs and demonstrate that the IEG framework achieves superior performance on both datasets, with over 9% F1 improvements in the few-shot setting for GPT-3.5&4 and other large language models (LLMs) and over 4.9% F1 enhancements in the fine-tuning setting for open-source BART."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Large Language Models

featured: true

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: OpenTE.pdf 
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
