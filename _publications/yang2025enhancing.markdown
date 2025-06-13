---
layout: publication
title: 'Enhancing Clinical Multiple-choice Questions Benchmarks With Knowledge Graph Guided Distractor Generation'
authors: Running Yang, Wenlong Deng, Minghui Chen, Yuyin Zhou, Xiaoxiao Li
conference: "Arxiv"
year: 2025
bibkey: yang2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00612"}
tags: ['Applications', 'Tools']
---
Clinical tasks such as diagnosis and treatment require strong decision-making abilities, highlighting the importance of rigorous evaluation benchmarks to assess the reliability of large language models (LLMs). In this work, we introduce a knowledge-guided data augmentation framework that enhances the difficulty of clinical multiple-choice question (MCQ) datasets by generating distractors (i.e., incorrect choices that are similar to the correct one and may confuse existing LLMs). Using our KG-based pipeline, the generated choices are both clinically plausible and deliberately misleading. Our approach involves multi-step, semantically informed walks on a medical knowledge graph to identify distractor paths-associations that are medically relevant but factually incorrect-which then guide the LLM in crafting more deceptive distractors. We apply the designed knowledge graph guided distractor generation (KGGDG) pipline, to six widely used medical QA benchmarks and show that it consistently reduces the accuracy of state-of-the-art LLMs. These findings establish KGGDG as a powerful tool for enabling more robust and diagnostic evaluations of medical LLMs.
