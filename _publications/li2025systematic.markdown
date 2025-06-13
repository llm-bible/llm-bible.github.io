---
layout: publication
title: 'SPADE: Systematic Prompt Framework For Automated Dialogue Expansion In Machine-generated Text Detection'
authors: Haoyi Li, Angela Yifei Yuan, Soyeon Caren Han, Christopher Leckie
conference: "Arxiv"
year: 2025
bibkey: li2025systematic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.15044'}
  - {name: "Code", url: 'https://github.com/AngieYYF/SPADE-customer-service-dialogue'}
tags: ['Agentic', 'Has Code', 'Training Techniques', 'Tools', 'Prompting', 'Reinforcement Learning']
---
The increasing capability of large language models (LLMs) to generate
synthetic content has heightened concerns about their misuse, driving the
development of Machine-Generated Text (MGT) detection models. However, these
detectors face significant challenges due to the lack of systematically
generated, high-quality datasets for training. To address this issue, we
propose five novel data augmentation frameworks for synthetic user dialogue
generation through a structured prompting approach, reducing the costs
associated with traditional data collection methods. Our proposed method yields
14 new dialogue datasets, which we benchmark against seven MGT detection
models. The results demonstrate improved generalization performance when
utilizing a mixed dataset produced by our proposed augmentation framework.
Furthermore, considering that real-world agents lack knowledge of future
opponent utterances, we simulate online dialogue detection and examine the
relationship between chat history length and detection accuracy. We also
benchmark online detection performance with limited chat history on our
frameworks. Our open-source datasets can be downloaded from
https://github.com/AngieYYF/SPADE-customer-service-dialogue.
