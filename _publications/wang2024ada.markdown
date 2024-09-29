---
layout: publication
title: Ada45;leval Evaluating Long45;context Llms With Length45;adaptable Benchmarks
authors: Wang Chonghua, Duan Haodong, Zhang Songyang, Lin Dahua, Chen Kai
conference: "Arxiv"
year: 2024
bibkey: wang2024ada
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06480"}
  - {name: "Code", url: "https://github.com/open&#45;compass/Ada&#45;LEval"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
Recently the large language model (LLM) community has shown increasing interest in enhancing LLMs capability to handle extremely long documents. As various long45;text techniques and model architectures emerge the precise and detailed evaluation of models long45;text capabilities has become increasingly important. Existing long45;text evaluation benchmarks such as L45;Eval and LongBench construct long45;text test sets based on open45;source datasets focusing mainly on QA and summarization tasks. These datasets include test samples of varying lengths (from 2k to 32k+) entangled together making it challenging to assess model capabilities across different length ranges. Moreover they do not cover the ultralong settings (100k+ tokens) that the latest LLMs claim to achieve. In this paper we introduce Ada45;LEval a length45;adaptable benchmark for evaluating the long45;context understanding of LLMs. Ada45;LEval includes two challenging subsets TSort and BestAnswer which enable a more reliable evaluation of LLMs long context capabilities. These benchmarks support intricate manipulation of the length of test cases and can easily produce text samples up to 128k tokens. We evaluate 4 state45;of45;the45;art closed45;source API models and 6 open45;source models with Ada45;LEval. The evaluation results demonstrate the limitations of current LLMs especially in ultra45;long45;context settings. Our code is available at https://github.com/open&#45;compass/Ada&#45;LEval.
