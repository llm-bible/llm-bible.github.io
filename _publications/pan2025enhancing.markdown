---
layout: publication
title: 'Enhancing The Geometric Problem-solving Ability Of Multimodal Llms Via Symbolic-neural Integration'
authors: Yicheng Pan, Zhenrong Zhang, Pengfei Hu, Jiefeng Ma, Jun Du, Jianshu Zhang, Quan Liu, Jianqing Gao, Feng Ma
conference: "Arxiv"
year: 2025
bibkey: pan2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12773"}
  - {name: "Code", url: "https://github.com/ycpNotFound/GeoGen"}
tags: ['RAG', 'Has Code', 'Tools', 'Multimodal Models']
---
Recent advances in Multimodal Large Language Models (MLLMs) have achieved
remarkable progress in general domains and demonstrated promise in multimodal
mathematical reasoning. However, applying MLLMs to geometry problem solving
(GPS) remains challenging due to lack of accurate step-by-step solution data
and severe hallucinations during reasoning. In this paper, we propose GeoGen, a
pipeline that can automatically generates step-wise reasoning paths for
geometry diagrams. By leveraging the precise symbolic reasoning,
\textbf\{GeoGen\} produces large-scale, high-quality question-answer pairs. To
further enhance the logical reasoning ability of MLLMs, we train
\textbf\{GeoLogic\}, a Large Language Model (LLM) using synthetic data generated
by GeoGen. Serving as a bridge between natural language and symbolic systems,
GeoLogic enables symbolic tools to help verifying MLLM outputs, making the
reasoning process more rigorous and alleviating hallucinations. Experimental
results show that our approach consistently improves the performance of MLLMs,
achieving remarkable results on benchmarks for geometric reasoning tasks. This
improvement stems from our integration of the strengths of LLMs and symbolic
systems, which enables a more reliable and interpretable approach for the GPS
task. Codes are available at https://github.com/ycpNotFound/GeoGen.
