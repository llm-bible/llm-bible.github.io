---
layout: publication
title: 'The Benefits Of A Concise Chain Of Thought On Problem-solving In Large Language Models'
authors: Matthew Renze, Erhan Guven
conference: "2nd International Conference on Foundation and Large Language Models (FLLM 2024) pp.476-483"
year: 2024
bibkey: renze2024benefits
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05618"}
  - {name: "Code", url: "https://github.com/matthewrenze/jhu-concise-cot"}
tags: ['Model Architecture', 'RAG', 'GPT', 'Has Code', 'Prompting']
---
In this paper, we introduce Concise Chain-of-Thought (CCoT) prompting. We
compared standard CoT and CCoT prompts to see how conciseness impacts response
length and correct-answer accuracy. We evaluated this using GPT-3.5 and GPT-4
with a multiple-choice question-and-answer (MCQA) benchmark. CCoT reduced
average response length by 48.70% for both GPT-3.5 and GPT-4 while having a
negligible impact on problem-solving performance. However, on math problems,
GPT-3.5 with CCoT incurs a performance penalty of 27.69%. Overall, CCoT leads
to an average per-token cost reduction of 22.67%. All code, data, and
supplemental materials are available on GitHub at
https://github.com/matthewrenze/jhu-concise-cot
