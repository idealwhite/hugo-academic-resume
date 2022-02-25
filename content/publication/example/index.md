---
abstract: Image inpainting task requires filling the corrupted image with
  contents coherent with the context. This research field has achieved promising
  progress by using neural image inpainting methods. Nevertheless, there is
  still a critical challenge in guessing the missed content with only the
  context pixels. The goal of this paper is to fill the semantic information in
  corrupted images according to the provided descriptive text. Unique from
  existing text-guided image generation works, the inpainting models are
  required to compare the semantic content of the given text and the remaining
  part of the image, then find out the semantic content that should be filled
  for missing part. To fulfill such a task, we propose a novel inpainting model
  named Text-Guided Dual Attention Inpainting Network (TDANet). Firstly, a dual
  multimodal attention mechanism is designed to extract the explicit semantic
  information about the corrupted regions, which is done by comparing the
  descriptive text and complementary image areas through reciprocal attention.
  Secondly, an image-text matching loss is applied to maximize the semantic
  similarity of the generated image and the text. Experiments are conducted on
  two open datasets. Results show that the proposed TDANet model reaches new
  state-of-the-art on both quantitative and qualitative measures. Result
  analysis suggests that the generated images are consistent with the guidance
  text, enabling the generation of various results by providing different
  description
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Lisai Zhang
  - Qingcai Chen
  - Baotian Hu
  - Shuoran Jiang
author_notes: []
publication: In *ACM MM 2020*, (Oral)
summary: ""
url_dataset: ""
url_project: ""
publication_short: In *ACM Multimedia 2020*
url_source: ""
url_video: ""
title: Text-Guided Neural Image Inpainting
subtitle: ""
doi: ""
featured: true
tags: []
projects: []
image:
  caption: "Illustration of inpainting a unique area. "
  focal_point: ""
  preview_only: false
  filename: featured.png
date: 2020-10-03T11:48:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Zhang L, Chen Q, Hu B, et al. Text-guided neural image inpainting[C]//Proceedings of the 28th ACM International Conference on Multimedia. 2020: 1302-1310.
{{% /callout %}}
