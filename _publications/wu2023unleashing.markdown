---
layout: publication
title: 'Unleashing Potential Of Evidence In Knowledge-intensive Dialogue Generation'
authors: Wu Xianjie, Yang Jian, Li Tongliang, Liang Di, Zhang Shiwei, Du Yiyang, Li Zhoujun
conference: "Arxiv"
year: 2023
bibkey: wu2023unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08380"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Incorporating external knowledge into dialogue generation (KIDG) is crucial
for improving the correctness of response, where evidence fragments serve as
knowledgeable snippets supporting the factual dialogue replies. However,
introducing irrelevant content often adversely impacts reply quality and easily
leads to hallucinated responses. Prior work on evidence retrieval and
integration in dialogue systems falls short of fully leveraging existing
evidence since the model fails to locate useful fragments accurately and
overlooks hidden evidence labels within the KIDG dataset. To fully Unleash the
potential of evidence, we propose a framework to effectively incorporate
Evidence in knowledge-Intensive Dialogue Generation (u-EIDG). Specifically, we
introduce an automatic evidence generation framework that harnesses the power
of Large Language Models (LLMs) to mine reliable evidence veracity labels from
unlabeled data. By utilizing these evidence labels, we train a reliable
evidence indicator to effectively identify relevant evidence from retrieved
passages. Furthermore, we propose an evidence-augmented generator with an
evidence-focused attention mechanism, which allows the model to concentrate on
evidenced segments. Experimental results on MultiDoc2Dial demonstrate the
efficacy of evidential label augmentation and refined attention mechanisms in
improving model performance. Further analysis confirms that the proposed method
outperforms other baselines (+3~+5 points) regarding coherence and factual
consistency.
