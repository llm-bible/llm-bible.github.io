---
layout: publication
title: 'Human-in-the-loop Machine Translation With Large Language Model'
authors: Yang Xinyi, Zhan Runzhe, Wong Derek F., Wu Junchao, Chao Lidia S.
conference: "Arxiv"
year: 2023
bibkey: yang2023human
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08908"}
  - {name: "Code", url: "https://github.com/NLP2CT/HIL-MT/"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Has Code', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
The large language model (LLM) has garnered significant attention due to its in-context learning mechanisms and emergent capabilities. The research community has conducted several pilot studies to apply LLMs to machine translation tasks and evaluate their performance from diverse perspectives. However previous research has primarily focused on the LLM itself and has not explored human intervention in the inference process of LLM. The characteristics of LLM such as in-context learning and prompt engineering closely mirror human cognitive abilities in language tasks offering an intuitive solution for human-in-the-loop generation. In this study we propose a human-in-the-loop pipeline that guides LLMs to produce customized outputs with revision instructions. The pipeline initiates by prompting the LLM to produce a draft translation followed by the utilization of automatic retrieval or human feedback as supervision signals to enhance the LLMs translation through in-context learning. The human-machine interactions generated in this pipeline are also stored in an external database to expand the in-context retrieval database enabling us to leverage human supervision in an offline setting. We evaluate the proposed pipeline using GPT-3.5-turbo API on five domain-specific benchmarks for German-English translation. The results demonstrate the effectiveness of the pipeline in tailoring in-domain translations and improving translation performance compared to direct translation. Additionally we discuss the results from the following perspectives 1) the effectiveness of different in-context retrieval methods; 2) the construction of a retrieval database under low-resource scenarios; 3) the observed domains differences; 4) the quantitative analysis of linguistic statistics; and 5) the qualitative analysis of translation cases. The code and data are available at https://github.com/NLP2CT/HIL-MT/."
