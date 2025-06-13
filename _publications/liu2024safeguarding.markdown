---
layout: publication
title: 'Expshield: Safeguarding Web Text From Unauthorized Crawling And Language Modeling Exploitation'
authors: Ruixuan Liu, Toan Tran, Tianhao Wang, Hongsheng Hu, Shuo Wang, Li Xiong
conference: "Arxiv"
year: 2024
bibkey: liu2024safeguarding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.21123"}
tags: ['Fine-Tuning', 'RAG', 'Language Modeling', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods']
---
As large language models (LLMs) increasingly depend on web-scraped datasets,
concerns arise over their potential to generate verbatim training content with
copyrighted or private information. However, current protections against web
crawling or sample-specific memorization are inherently limited, as they
require compliance from crawlers (e.g., respecting robots.txt) or model
trainers (e.g., applying differential privacy). To empower data owners with
direct control, we propose ExpShiled, a proactive self-defense mechanism that
mitigates sample-specific memorization via imperceptible text perturbations.
This approach requires no external collaboration while maintaining original
readability. To evaluate individual-level defense efficacy, we first propose
the metric of instance exploitation: a zero value indicates perfect defense,
achieved when a protected text's log-perplexity ranking aligns with its
counterfactual untrained ranking. We then reveal and validate the memorization
trigger hypothesis, demonstrating that a model's memorization of a specific
text sample stems primarily from its outlier tokens. Leveraging this insight,
we design targeted perturbations that (1) prioritize inherent trigger tokens
and (2) introduce artificial trigger tokens as pitfalls to disrupt memorization
on the protected sample. Experiments validate our defense across model scales,
languages, vision-to-language tasks, and fine-tuning methods. Even with privacy
backdoors, the Membership Inference Attack (MIA) AUC drops from 0.95 to 0.55,
and instance exploitation approaches zero. This suggests that compared to the
ideal no-misuse scenario, the risk of exposing a text instance remains nearly
unchanged despite its inclusion in training data.
