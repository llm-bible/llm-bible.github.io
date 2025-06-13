---
layout: publication
title: 'Can Llms Solve Longer Math Word Problems Better?'
authors: Xin Xu, Tong Xiao, Zitong Chao, Zhenya Huang, Can Yang, Yang Wang
conference: "International Conference on Learning Representations (ICLR 2025)"
year: 2024
bibkey: xu2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14804"}
tags: ['Prompting', 'Pretraining Methods', 'Training Techniques', 'Fine-Tuning']
---
Math Word Problems (MWPs) play a vital role in assessing the capabilities of
Large Language Models (LLMs), yet current research primarily focuses on
questions with concise contexts. The impact of longer contexts on mathematical
reasoning remains under-explored. This study pioneers the investigation of
Context Length Generalizability (CoLeG), which refers to the ability of LLMs to
solve MWPs with extended narratives. We introduce Extended Grade-School Math
(E-GSM), a collection of MWPs featuring lengthy narratives, and propose two
novel metrics to evaluate the efficacy and resilience of LLMs in tackling these
problems. Our analysis of existing zero-shot prompting techniques with
proprietary LLMs along with open-source LLMs reveals a general deficiency in
CoLeG. To alleviate these issues, we propose tailored approaches for different
categories of LLMs. For proprietary LLMs, we introduce a new instructional
prompt designed to mitigate the impact of long contexts. For open-source LLMs,
we develop a novel auxiliary task for fine-tuning to enhance CoLeG. Our
comprehensive results demonstrate the effectiveness of our proposed methods,
showing improved performance on E-GSM. Additionally, we conduct an in-depth
analysis to differentiate the effects of semantic understanding and reasoning
efficacy, showing that our methods improves the latter. We also establish the
generalizability of our methods across several other MWP benchmarks. Our
findings highlight the limitations of current LLMs and offer practical
solutions correspondingly, paving the way for further exploration of model
generalizability and training methodologies.
