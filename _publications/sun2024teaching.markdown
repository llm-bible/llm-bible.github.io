---
layout: publication
title: 'Surf: Teaching Large Vision-language Models To Selectively Utilize Retrieved Information'
authors: Jiashuo Sun, Jihai Zhang, Yucheng Zhou, Zhaochen Su, Xiaoye Qu, Yu Cheng
conference: "Arxiv"
year: 2024
bibkey: sun2024teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.14083"}
  - {name: "Code", url: "https://github.com/GasolSun36/SURf"}
tags: ['Security', 'Multimodal Models', 'Tools', 'RAG', 'Has Code']
---
Large Vision-Language Models (LVLMs) have become pivotal at the intersection
of computer vision and natural language processing. However, the full potential
of LVLMs Retrieval-Augmented Generation (RAG) capabilities remains
underutilized. Existing works either focus solely on the text modality or are
limited to specific tasks. Moreover, most LVLMs struggle to selectively utilize
retrieved information and are sensitive to irrelevant or misleading references.
To address these challenges, we propose a self-refinement framework designed to
teach LVLMs to Selectively Utilize Retrieved Information (SURf). Specifically,
when given questions that are incorrectly answered by the LVLM backbone, we
obtain references that help correct the answers (positive references) and those
that do not (negative references). We then fine-tune the LVLM backbone using a
combination of these positive and negative references. Our experiments across
three tasks and seven datasets demonstrate that our framework significantly
enhances LVLMs ability to effectively utilize retrieved multimodal references
and improves their robustness against irrelevant or misleading information. The
source code is available at https://github.com/GasolSun36/SURf.
