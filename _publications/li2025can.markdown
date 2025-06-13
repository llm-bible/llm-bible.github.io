---
layout: publication
title: 'Arxivbench: Can Llms Assist Researchers In Conducting Research?'
authors: Ning Li, Jingran Zhang, Justin Cui
conference: "Arxiv"
year: 2025
bibkey: li2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10496"}
  - {name: "Code", url: "https://github.com/arxivBenchLLM/arXivBench"}
  - {name: "Code", url: "https://huggingface.co/datasets/arXivBenchLLM/arXivBench"}
tags: ['Prompting', 'Arxiv', 'Has Code', 'Tools']
---
Large language models (LLMs) have demonstrated remarkable effectiveness in
completing various tasks such as reasoning, translation, and question
answering. However the issue of factual incorrect content in LLM-generated
responses remains a persistent challenge. In this study, we evaluate both
proprietary and open-source LLMs on their ability to respond with relevant
research papers and accurate links to articles hosted on the arXiv platform,
based on high level prompts. To facilitate this evaluation, we introduce
arXivBench, a benchmark specifically designed to assess LLM performance across
eight major subject categories on arXiv and five subfields within computer
science, one of the most popular categories among them. Our findings reveal a
concerning accuracy of LLM-generated responses depending on the subject, with
some subjects experiencing significantly lower accuracy than others. Notably,
Claude-3.5-Sonnet exhibits a substantial advantage in generating both relevant
and accurate responses. And interestingly, most LLMs achieve a much higher
accuracy in the Artificial Intelligence sub-field than other sub-fields. This
benchmark provides a standardized tool for evaluating the reliability of
LLM-generated scientific responses, promoting more dependable use of LLMs in
academic and research environments. Our code is open-sourced at
https://github.com/arxivBenchLLM/arXivBench and our dataset is available on
huggingface at https://huggingface.co/datasets/arXivBenchLLM/arXivBench.
