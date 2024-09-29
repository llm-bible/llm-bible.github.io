---
layout: publication
title: Teaching Large Language Models To Self45;debug
authors: Chen Xinyun, Lin Maxwell, Schärli Nathanael, Zhou Denny
conference: "Arxiv"
year: 2023
bibkey: chen2023teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.05128"}
tags: ['Applications', 'Efficiency And Optimization', 'Interpretability And Explainability', 'RAG']
---
Large language models (LLMs) have achieved impressive performance on code generation. However for complex programming tasks generating the correct solution in one go becomes challenging thus some prior works have designed program repair approaches to improve code generation performance. In this work we propose Self45;Debugging which teaches a large language model to debug its predicted program via few45;shot demonstrations. In particular we demonstrate that Self45;Debugging can teach the large language model to perform rubber duck debugging; i.e. without any human feedback on the code correctness or error messages the model is able to identify its mistakes by investigating the execution results and explaining the generated code in natural language. Self45;Debugging achieves the state45;of45;the45;art performance on several code generation benchmarks including the Spider dataset for text45;to45;SQL generation TransCoder for C++45;to45;Python translation and MBPP for text45;to45;Python generation. On the Spider benchmark where there are no unit tests to verify the correctness of predictions Self45;Debugging with code explanation consistently improves the baseline by 245;337; and improves the prediction accuracy on problems of the hardest level by 937;. On TransCoder and MBPP where unit tests are available Self45;Debugging improves the baseline accuracy by up to 1237;. Meanwhile by leveraging feedback messages and reusing failed predictions Self45;Debugging notably improves sample efficiency and can match or outperform baseline models that generate more than 10x candidate programs.
