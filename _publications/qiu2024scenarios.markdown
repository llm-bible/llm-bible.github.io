---
layout: publication
title: Scenarios And Approaches For Situated Natural Language Explanations
authors: Qiu Pengshuo, Rudzicz Frank, Zhu Zining
conference: "Arxiv"
year: 2024
bibkey: qiu2024scenarios
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05035"}
tags: ['Interpretability And Explainability', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) can be used to generate natural language explanations (NLE) that are adapted to different users situations. However there is yet to be a quantitative evaluation of the extent of such adaptation. To bridge this gap we collect a benchmarking dataset Situation45;Based Explanation. This dataset contains 100 explanandums. Each explanandum is paired with explanations targeted at three distinct audience types45;such as educators students and professionals45;enabling us to assess how well the explanations meet the specific informational needs and contexts of these diverse groups e.g. students teachers and parents. For each explanandum paired with an audience situation we include a human45;written explanation. These allow us to compute scores that quantify how the LLMs adapt the explanations to the situations. On an array of pretrained language models with varying sizes we examine three categories of prompting methods rule45;based prompting meta45;prompting and in45;context learning prompting. We find that 1) language models can generate prompts that result in explanations more precisely aligned with the target situations 2) explicitly modeling an assistant persona by prompting You are a helpful assistant... is not a necessary prompt technique for situated NLE tasks and 3) the in45;context learning prompts only can help LLMs learn the demonstration template but cant improve their inference performance. SBE and our analysis facilitate future research towards generating situated natural language explanations.
