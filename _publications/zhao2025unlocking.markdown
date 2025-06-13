---
layout: publication
title: 'Favchat: Unlocking Fine-grained Facial Video Understanding With Multimodal Large Language Models'
authors: Fufangchen Zhao, Ming Li, Linrui Xu, Wenhao Jiang, Jian Gao, Danfeng Yan
conference: "Arxiv"
year: 2025
bibkey: zhao2025unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.09158"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Merging', 'GPT', 'Applications']
---
Video-based multimodal large language models (VMLLMs) have demonstrated
remarkable potential in cross-modal video understanding. However, their
abilities in fine-grained face comprehension remain largely underexplored.
Given its pivotal role in human-centric intelligence, developing VMLLMs for
facial understanding holds a fundamental problem. To address this gap, we
propose FaVChat, the first VMLLM specifically designed for fine-grained facial
video understanding. To facilitate its training, we construct a large-scale
facial video dataset comprising over 60k videos, with the majority annotated
with 83 fine-grained facial attributes. These attributes are incorporated to
enrich GPT-4o-generated captions, yielding 60k high-quality video-summary pairs
and an additional 170k fine-grained question-answering (QA) pairs. To
effectively capture rich facial clues, we propose a hybrid model architecture
composed of a general visual encoder, a dedicated facial encoder, and a
mixture-of-experts-enhanced adapter for adaptive fusion of multi-source visual
features. To mitigate information loss during feature transformation, we
extract multi-granularity representations from the facial encoder and integrate
them into the subsequent LLM. This design enhances the model's ability to
comprehend and respond to questions involving diverse levels of visual details.
We employ a progressive training paradigm, transitioning from video
summarization to a high-quality subset of video QA, gradually increasing task
complexity to enhance the model's fine-grained visual perception. We conduct
extensive zero-shot evaluation on a couple of public benchmarks, demonstrating
that FaVChat consistently surpasses existing VMLLMs across multiple tasks.
