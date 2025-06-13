---
layout: publication
title: 'Synergistic Weak-strong Collaboration By Aligning Preferences'
authors: Yizhu Jiao, Xuchao Zhang, Zhaoyang Wang, Yubo Ma, Zhun Deng, Rujia Wang, Chetan Bansal, Saravan Rajmohan, Jiawei Han, Huaxiu Yao
conference: "Arxiv"
year: 2025
bibkey: jiao2025synergistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15188"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Current Large Language Models (LLMs) excel in general reasoning yet struggle
with specialized tasks requiring proprietary or domain-specific knowledge.
Fine-tuning large models for every niche application is often infeasible due to
black-box constraints and high computational overhead. To address this, we
propose a collaborative framework that pairs a specialized weak model with a
general strong model. The weak model, tailored to specific domains, produces
initial drafts and background information, while the strong model leverages its
advanced reasoning to refine these drafts, extending LLMs' capabilities to
critical yet specialized tasks. To optimize this collaboration, we introduce a
collaborative feedback to fine-tunes the weak model, which quantifies the
influence of the weak model's contributions in the collaboration procedure and
establishes preference pairs to guide preference tuning of the weak model. We
validate our framework through experiments on three domains. We find that the
collaboration significantly outperforms each model alone by leveraging
complementary strengths. Moreover, aligning the weak model with the
collaborative preference further enhances overall performance.
