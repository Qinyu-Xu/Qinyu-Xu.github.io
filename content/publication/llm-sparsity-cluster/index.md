---
title: 'Tactic: Thresholding Accumulated Weight Via Clustering and Curve Fitting for Sparse Attention in Long-Context Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2025-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['in preparation']

# Publication name and optional abbreviated publication name.
# publication: In *Hugo Blox Builder Conference*
# publication_short: In *ICW*

abstract: Long-context models are increasingly important in daily applications, but their inference is hindered by inefficiencies caused by loading large KV Cache during decoding. Prior work has shown that attention is inherently sparse, with a small subset of tokens significantly influencing model output. To utilize sparsity, most existing methods rely on a predefined token budget for attention computation. However, our analysis reveals that attention sparsity is inherently context-dependent, varying significantly with the specific generation context and different types of tasks. This variability highlights the need for a dynamic token budget and exposes the limitations of current methods in adapting to changing sparsity patterns. To address these challenges, we propose Tactic, a context-adaptive sparse attention mechanism for efficient and accurate long-context model inference. The key insight behind Tactic is to focus on the accumulated attention score to dynamically adjust the token budget, rather than relying on a predefined fixed budget. Since computing attention weights for the entire sequence is computationally expensive, Tactic introduces a distribution fitting technique to efficiently estimate attention weights with minimal computation.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'tactic.pdf'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
