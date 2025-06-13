---
layout: publication
title: 'Tinydrive: Multiscale Visual Question Answering With Selective Token Routing For Autonomous Driving'
authors: Hossein Hassani, Soodeh Nikan, Abdallah Shami
conference: "Arxiv"
year: 2025
bibkey: hassani2025multiscale
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.15564'}
tags: ['Applications', 'Training Techniques']
---
Vision Language Models (VLMs) employed for visual question-answering (VQA) in autonomous driving often require substantial computational resources that pose a challenge for their deployment in resource-constrained vehicles. To address this challenge, we introduce TinyDrive, a lightweight yet effective VLM for multi-view VQA in driving scenarios. Our model comprises two key components including a multiscale vision encoder and a dual-level prioritization mechanism for tokens and sequences. The multiscale encoder facilitates the processing of multi-view images at diverse resolutions through scale injection and cross-scale gating to generate enhanced visual representations. At the token level, we design a token routing mechanism that dynamically selects and process the most informative tokens based on learned importance scores. At the sequence level, we propose integrating normalized loss, uncertainty estimates, and a diversity metric to formulate sequence scores that rank and preserve samples within a sequence priority buffer. Samples with higher scores are more frequently selected for training. TinyDrive is first evaluated on our custom-curated VQA dataset, and it is subsequently tested on the public DriveLM benchmark, where it achieves state-of-the-art language understanding performance. Notably, it achieves relative improvements of 11.1% and 35.4% in BLEU-4 and METEOR scores, respectively, despite having a significantly smaller parameter count.
