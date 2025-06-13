---
layout: publication
title: 'Easyjudge: An Easy-to-use Tool For Comprehensive Response Evaluation Of Llms'
authors: Yijie Li, Yuan Sun
conference: "Arxiv"
year: 2024
bibkey: li2024easy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09775"}
tags: ['Efficiency and Optimization', 'GPT', 'Ethics and Bias', 'Model Architecture', 'Interpretability', 'Prompting']
---
Recently, there has been a growing trend of employing large language models
(LLMs) to judge the quality of other LLMs. Many studies have adopted
closed-source models, mainly using GPT-4 as the evaluator. However, due to the
closed-source nature of the GPT-4 model, employing it as an evaluator has
resulted in issues including transparency, controllability, and
cost-effectiveness. Some researchers have turned to using fine-tuned
open-source LLMs as evaluators. However, existing open-source evaluation LLMs
generally lack a user-friendly visualization tool, and they have not been
optimized for accelerated model inference, which causes inconvenience for
researchers with limited resources and those working across different fields.
This paper presents EasyJudge, a model developed to evaluate significant
language model responses. It is lightweight, precise, efficient, and
user-friendly, featuring an intuitive visualization interface for ease of
deployment and use. EasyJudge uses detailed datasets and refined prompts for
model optimization, achieving strong consistency with human and proprietary
model evaluations. The model optimized with quantitative methods enables
EasyJudge to run efficiently on consumer-grade GPUs or even CPUs. We also
provide detailed analysis and case studies to further reveal the potential of
our method.
