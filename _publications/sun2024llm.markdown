---
layout: publication
title: 'Llm-oriented Retrieval Tuner'
authors: Si Sun, Hanqing Zhang, Zhiyuan Liu, Jie Bao, Dawei Song
conference: "Arxiv"
year: 2024
bibkey: sun2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01999"}
tags: ['Language Modeling', 'Model Architecture', 'Applications', 'GPT']
---
Dense Retrieval (DR) is now considered as a promising tool to enhance the
memorization capacity of Large Language Models (LLM) such as GPT3 and GPT-4 by
incorporating external memories. However, due to the paradigm discrepancy
between text generation of LLM and DR, it is still an open challenge to
integrate the retrieval and generation tasks in a shared LLM. In this paper, we
propose an efficient LLM-Oriented Retrieval Tuner, namely LMORT, which
decouples DR capacity from base LLM and non-invasively coordinates the
optimally aligned and uniform layers of the LLM towards a unified DR space,
achieving an efficient and effective DR without tuning the LLM itself. The
extensive experiments on six BEIR datasets show that our approach could achieve
competitive zero-shot retrieval performance compared to a range of strong DR
models while maintaining the generation ability of LLM.
