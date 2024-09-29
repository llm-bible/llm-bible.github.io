---
layout: publication
title: Ice45;score Instructing Large Language Models To Evaluate Code
authors: Zhuo Terry Yue
conference: "Arxiv"
year: 2023
bibkey: zhuo2023ice
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.14317"}
  - {name: "Code", url: "https://github.com/terryyz/ice&#45;score&#125;&#125;,"}
tags: ['Applications', 'Has Code', 'RAG', 'Reinforcement Learning', 'TACL']
---
Recent advancements in the field of natural language generation have facilitated the use of large language models to assess the quality of generated text. Although these models have shown promising results in tasks such as machine translation and summarization their applicability in code intelligence tasks remains limited without human involvement. The complexity of programming concepts required for such tasks makes it difficult to develop evaluation metrics that align with human judgment. Token45;matching45;based metrics such as BLEU have demonstrated weak correlations with human practitioners in code intelligence tasks. Moreover utilizing human45;written test suites to evaluate functional correctness can be challenging in domains with low resources. To overcome these obstacles we propose texttt123;ICE45;Score125; a new evaluation metric via instructing large language models (LLMs) for code assessments. Our metric addresses the limitations of existing approaches by achieving superior correlations with functional correctness and human preferences without the need for test oracles or references. We evaluate the efficacy of our metric on two different aspects (textit123;human preference125; and textit123;execution success125;) and four programming languages. Our results demonstrate that our metric surpasses state45;of45;the45;art metrics for code generation delivering high levels of accuracy and consistency across various programming languages and tasks. We also make our evaluation metric and datasets available to the publicfootnote123;url123;https://github.com/terryyz/ice&#45;score&#125;&#125;, encouraging further research in evaluating code intelligence tasks.
