---
layout: publication
title: 'Controlling Out-of-domain Gaps In Llms For Genre Classification And Generated Text Detection'
authors: Dmitri Roussinov, Serge Sharoff, Nadezhda Puchnina
conference: "Arxiv"
year: 2024
bibkey: roussinov2024controlling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20595"}
tags: ['GPT', 'Model Architecture', 'BERT', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
This study demonstrates that the modern generation of Large Language Models
(LLMs, such as GPT-4) suffers from the same out-of-domain (OOD) performance gap
observed in prior research on pre-trained Language Models (PLMs, such as BERT).
We demonstrate this across two non-topical classification tasks: 1) genre
classification and 2) generated text detection. Our results show that when
demonstration examples for In-Context Learning (ICL) come from one domain
(e.g., travel) and the system is tested on another domain (e.g., history),
classification performance declines significantly.
  To address this, we introduce a method that controls which predictive
indicators are used and which are excluded during classification. For the two
tasks studied here, this ensures that topical features are omitted, while the
model is guided to focus on stylistic rather than content-based attributes.
This approach reduces the OOD gap by up to 20 percentage points in a few-shot
setup. Straightforward Chain-of-Thought (CoT) methods, used as the baseline,
prove insufficient, while our approach consistently enhances domain transfer
performance.
