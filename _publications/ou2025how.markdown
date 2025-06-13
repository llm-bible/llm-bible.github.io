---
layout: publication
title: 'CLAIMCHECK: How Grounded Are LLM Critiques Of Scientific Papers?'
authors: Jiefu Ou, William Gantt Walden, Kate Sanders, Zhengping Jiang, Kaiser Sun, Jeffrey Cheng, William Jurayj, Miriam Wanner, Shaobo Liang, Candice Morgan, Seunghoon Han, Weiqi Wang, Chandler May, Hannah Recknor, Daniel Khashabi, Benjamin Van Durme
conference: "Arxiv"
year: 2025
bibkey: ou2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.21717"}
tags: ['Survey Paper', 'NeurIPS', 'Reinforcement Learning']
---
A core part of scientific peer review involves providing expert critiques
that directly assess the scientific claims a paper makes. While it is now
possible to automatically generate plausible (if generic) reviews, ensuring
that these reviews are sound and grounded in the papers' claims remains
challenging. To facilitate LLM benchmarking on these challenges, we introduce
CLAIMCHECK, an annotated dataset of NeurIPS 2023 and 2024 submissions and
reviews mined from OpenReview. CLAIMCHECK is richly annotated by ML experts for
weakness statements in the reviews and the paper claims that they dispute, as
well as fine-grained labels of the validity, objectivity, and type of the
identified weaknesses. We benchmark several LLMs on three claim-centric tasks
supported by CLAIMCHECK, requiring models to (1) associate weaknesses with the
claims they dispute, (2) predict fine-grained labels for weaknesses and rewrite
the weaknesses to enhance their specificity, and (3) verify a paper's claims
with grounded reasoning. Our experiments reveal that cutting-edge LLMs, while
capable of predicting weakness labels in (2), continue to underperform relative
to human experts on all other tasks.
