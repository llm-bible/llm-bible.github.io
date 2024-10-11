---
layout: publication
title: 'Meerkat: Audio-visual Large Language Model For Grounding In Space And Time'
authors: Chowdhury Sanjoy, Nag Sayan, Dasgupta Subhrajyoti, Chen Jun, Elhoseiny Mohamed, Gao Ruohan, Manocha Dinesh
conference: "Arxiv"
year: 2024
bibkey: chowdhury2024audio
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01851"}
tags: ['Attention Mechanism', 'Model Architecture', 'RAG', 'Uncategorized']
---
Leveraging Large Language Models' remarkable proficiency in text-based tasks, recent works on Multi-modal LLMs (MLLMs) extend them to other modalities like vision and audio. However, the progress in these directions has been mostly focused on tasks that only require a coarse-grained understanding of the audio-visual semantics. We present Meerkat, an audio-visual LLM equipped with a fine-grained understanding of image and audio both spatially and temporally. With a new modality alignment module based on optimal transport and a cross-attention module that enforces audio-visual consistency, Meerkat can tackle challenging tasks such as audio referred image grounding, image guided audio temporal localization, and audio-visual fact-checking. Moreover, we carefully curate a large dataset AVFIT that comprises 3M instruction tuning samples collected from open-source datasets, and introduce MeerkatBench that unifies five challenging audio-visual tasks. We achieve state-of-the-art performance on all these downstream tasks with a relative improvement of up to 37.12&#37;.
