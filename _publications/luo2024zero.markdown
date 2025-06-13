---
layout: publication
title: 'Zero-shot Image Moderation In Google Ads With Llm-assisted Textual Descriptions And Cross-modal Co-embeddings'
authors: Enming Luo, Wei Qiao, Katie Warren, Jingxiang Li, Eric Xiao, Krishna Viswanathan, Yuan Wang, Yintao Liu, Jimin Li, Ariel Fuxman
conference: "Arxiv"
year: 2024
bibkey: luo2024zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16215"}
tags: ['RAG', 'Training Techniques', 'Multimodal Models', 'Tools']
---
We present a scalable and agile approach for ads image content moderation at
Google, addressing the challenges of moderating massive volumes of ads with
diverse content and evolving policies. The proposed method utilizes
human-curated textual descriptions and cross-modal text-image co-embeddings to
enable zero-shot classification of policy violating ads images, bypassing the
need for extensive supervised training data and human labeling. By leveraging
large language models (LLMs) and user expertise, the system generates and
refines a comprehensive set of textual descriptions representing policy
guidelines. During inference, co-embedding similarity between incoming images
and the textual descriptions serves as a reliable signal for policy violation
detection, enabling efficient and adaptable ads content moderation. Evaluation
results demonstrate the efficacy of this framework in significantly boosting
the detection of policy violating content.
