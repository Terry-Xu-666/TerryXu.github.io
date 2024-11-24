---
title: "Thinking Before Looking: Improving Multimodal LLM Reasoning via Mitigating Visual Hallucination"
authors: ["Haojie Zheng*","admin*","Ryan Sun","Shu Pu","Ruoxi Chen","Lichao Sun"]
author_notes:
- Equal contribution
- Equal contribution

date: "2024-11-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Multimodal large language models (MLLMs) have advanced the integration of visual and linguistic modalities, establishing themselves as the dominant paradigm for visual-language tasks. Current approaches like chain of thought (CoT) reasoning have augmented the cognitive capabilities of large language models (LLMs), yet their adaptation to MLLMs is hindered by heightened risks of hallucination in cross-modality comprehension. In this paper, we find that the thinking while looking paradigm in current multimodal CoT approaches--where reasoning chains are generated alongside visual input--fails to mitigate hallucinations caused by misleading images. To address these limitations, we propose the Visual Inference Chain (VIC) framework, a novel approach that constructs reasoning chains using textual context alone before introducing visual input, effectively reducing cross-modal biases and enhancing multimodal reasoning accuracy. Comprehensive evaluations demonstrate that VIC significantly improves zero-shot performance across various vision-related tasks, mitigating hallucinations while refining the reasoning capabilities of MLLMs.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Multimodal Large Language Models
- Reasoning

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2411.12591
url_code: https://github.com/Terry-Xu-666/visual_inference_chain
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'This example from HallusionBench demonstrates the differences between zero-shot, zero-shot CoT, and VIC. The zero-shot CoT represents the \textit{thinking while looking} approach, which tends to exhibit stereotypical reasoning patterns when processing both visual and textual inputs simultaneously. In contrast, our thinking before looking paradigm, VIC, enhances reasoning quality by decoupling the visual and textual inputs.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
