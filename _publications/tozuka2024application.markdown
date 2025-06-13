---
layout: publication
title: 'Application Of Notebooklm, A Large Language Model With Retrieval-augmented Generation, For Lung Cancer Staging'
authors: Ryota Tozuka, Hisashi Johno, Akitomo Amakawa, Junichi Sato, Mizuki Muto, Shoichiro Seki, Atsushi Komaba, Hiroshi Onishi
conference: "Arxiv"
year: 2024
bibkey: tozuka2024application
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.10869'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Applications', 'Tools', 'GPT']
---
Purpose: In radiology, large language models (LLMs), including ChatGPT, have
recently gained attention, and their utility is being rapidly evaluated.
However, concerns have emerged regarding their reliability in clinical
applications due to limitations such as hallucinations and insufficient
referencing. To address these issues, we focus on the latest technology,
retrieval-augmented generation (RAG), which enables LLMs to reference reliable
external knowledge (REK). Specifically, this study examines the utility and
reliability of a recently released RAG-equipped LLM (RAG-LLM), NotebookLM, for
staging lung cancer.
  Materials and methods: We summarized the current lung cancer staging
guideline in Japan and provided this as REK to NotebookLM. We then tasked
NotebookLM with staging 100 fictional lung cancer cases based on CT findings
and evaluated its accuracy. For comparison, we performed the same task using a
gold-standard LLM, GPT-4 Omni (GPT-4o), both with and without the REK.
  Results: NotebookLM achieved 86% diagnostic accuracy in the lung cancer
staging experiment, outperforming GPT-4o, which recorded 39% accuracy with the
REK and 25% without it. Moreover, NotebookLM demonstrated 95% accuracy in
searching reference locations within the REK.
  Conclusion: NotebookLM successfully performed lung cancer staging by
utilizing the REK, demonstrating superior performance compared to GPT-4o.
Additionally, it provided highly accurate reference locations within the REK,
allowing radiologists to efficiently evaluate the reliability of NotebookLM's
responses and detect possible hallucinations. Overall, this study highlights
the potential of NotebookLM, a RAG-LLM, in image diagnosis.
