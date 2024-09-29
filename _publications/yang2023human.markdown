---
layout: publication
title: Human45;in45;the45;loop Machine Translation With Large Language Model
authors: Yang Xinyi, Zhan Runzhe, Wong Derek F., Wu Junchao, Chao Lidia S.
conference: "Arxiv"
year: 2023
bibkey: yang2023human
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08908"}
  - {name: "Code", url: "https://github.com/NLP2CT/HIL&#45;MT/"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
The large language model (LLM) has garnered significant attention due to its in45;context learning mechanisms and emergent capabilities. The research community has conducted several pilot studies to apply LLMs to machine translation tasks and evaluate their performance from diverse perspectives. However previous research has primarily focused on the LLM itself and has not explored human intervention in the inference process of LLM. The characteristics of LLM such as in45;context learning and prompt engineering closely mirror human cognitive abilities in language tasks offering an intuitive solution for human45;in45;the45;loop generation. In this study we propose a human45;in45;the45;loop pipeline that guides LLMs to produce customized outputs with revision instructions. The pipeline initiates by prompting the LLM to produce a draft translation followed by the utilization of automatic retrieval or human feedback as supervision signals to enhance the LLMs translation through in45;context learning. The human45;machine interactions generated in this pipeline are also stored in an external database to expand the in45;context retrieval database enabling us to leverage human supervision in an offline setting. We evaluate the proposed pipeline using GPT45;3.545;turbo API on five domain45;specific benchmarks for German45;English translation. The results demonstrate the effectiveness of the pipeline in tailoring in45;domain translations and improving translation performance compared to direct translation. Additionally we discuss the results from the following perspectives 1) the effectiveness of different in45;context retrieval methods; 2) the construction of a retrieval database under low45;resource scenarios; 3) the observed domains differences; 4) the quantitative analysis of linguistic statistics; and 5) the qualitative analysis of translation cases. The code and data are available at https://github.com/NLP2CT/HIL&#45;MT/.
