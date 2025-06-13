---
layout: publication
title: 'Empowering AI To Generate Better AI Code: Guided Generation Of Deep Learning Projects With Llms'
authors: Chen Xie, Mingsheng Jiao, Xiaodong Gu, Beijun Shen
conference: "Arxiv"
year: 2025
bibkey: xie2025empowering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.15080'}
tags: ['RAG', 'Applications']
---
While large language models (LLMs) have been widely applied to code
generation, they struggle with generating entire deep learning projects, which
are characterized by complex structures, longer functions, and stronger
reliance on domain knowledge than general-purpose code. An open-domain LLM
often lacks coherent contextual guidance and domain expertise for specific
projects, making it challenging to produce complete code that fully meets user
requirements.
  In this paper, we propose a novel planning-guided code generation method,
DLCodeGen, tailored for generating deep learning projects. DLCodeGen predicts a
structured solution plan, offering global guidance for LLMs to generate the
project. The generated plan is then leveraged to retrieve semantically
analogous code samples and subsequently abstract a code template. To
effectively integrate these multiple retrieval-augmented techniques, a
comparative learning mechanism is designed to generate the final code. We
validate the effectiveness of our approach on a dataset we build for deep
learning code generation. Experimental results demonstrate that DLCodeGen
outperforms other baselines, achieving improvements of 9.7% in CodeBLEU and
3.6% in human evaluation metrics.
