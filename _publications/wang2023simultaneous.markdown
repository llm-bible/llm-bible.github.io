---
layout: publication
title: 'Simultaneous Machine Translation With Large Language Models'
authors: Wang Minghan, Zhao Jinming, Vu Thuy-trang, Shiri Fatemeh, Shareghi Ehsan, Haffari Gholamreza
conference: "Arxiv"
year: 2023
bibkey: wang2023simultaneous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.06706"}
tags: ['Applications', 'Efficiency And Optimization', 'Reinforcement Learning', 'Security', 'TACL']
---
"Real-world simultaneous machine translation (SimulMT) systems face more challenges than just the quality-latency trade-off. They also need to address issues related to robustness with noisy input, processing long contexts, and flexibility for knowledge injection. These challenges demand models with strong language understanding and generation capabilities which may not often equipped by dedicated MT models. In this paper, we investigate the possibility of applying Large Language Models (LLM) to SimulMT tasks by using existing incremental-decoding methods with a newly proposed RALCP algorithm for latency reduction. We conducted experiments using the \texttt\{Llama2-7b-chat\} model on nine different languages from the MUST-C dataset. The results show that LLM outperforms dedicated MT models in terms of BLEU and LAAL metrics. Further analysis indicates that LLM has advantages in terms of tuning efficiency and robustness. However, it is important to note that the computational cost of LLM remains a significant obstacle to its application in SimulMT.\footnote\{We will release our code, weights, and data with publication.\}"
