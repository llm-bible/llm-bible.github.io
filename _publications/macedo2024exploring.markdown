---
layout: publication
title: 'Exploring The Impact Of The Output Format On The Evaluation Of Large Language Models For Code Translation'
authors: Macedo Marcos, Tian Yuan, Cogo Filipe R., Adams Bram
conference: "Arxiv"
year: 2024
bibkey: macedo2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17214"}
tags: ['Applications', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Code translation between programming languages is a long-existing and critical task in software engineering facilitating the modernization of legacy systems ensuring cross-platform compatibility and enhancing software performance. With the recent advances in large language models (LLMs) and their applications to code translation there is an increasing need for comprehensive evaluation of these models. In this study we empirically analyze the generated outputs of eleven popular instruct-tuned LLMs with parameters ranging from 1B up to 46.7B on 3820 translation pairs across five languages including C C++ Go Java and Python. Our analysis found that between 26.437; and 73.737; of code translations produced by our evaluated LLMs necessitate post-processing as these translations often include a mix of code quotes and text rather than being purely source code. Overlooking the output format of these models can inadvertently lead to underestimation of their actual performance. This is particularly evident when evaluating them with execution-based metrics such as Computational Accuracy (CA). Our results demonstrate that a strategic combination of prompt engineering and regular expression can effectively extract the source code from the model generation output. In particular our method can help eleven selected models achieve an average Code Extraction Success Rate (CSR) of 92.7337;. Our findings shed light on and motivate future research to conduct more reliable benchmarks of LLMs for code translation.
