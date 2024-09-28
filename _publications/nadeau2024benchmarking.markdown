---
layout: publication
title: Benchmarking Llama2 Mistral Gemma and GPT for Factuality Toxicity Bias and Propensity for Hallucinations
authors: Nadeau David, Kroutikov Mike, Mcneil Karen, Baribeau Simon
conference: "Arxiv"
year: 2024
bibkey: nadeau2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09785"}
tags: ['ARXIV', 'Ethics And Bias', 'GPT', 'Prompting', 'Responsible AI']
---
This paper introduces fourteen novel datasets for the evaluation of Large Language Models safety in the context of enterprise tasks. A method was devised to evaluate a models safety as determined by its ability to follow instructions and output factual unbiased grounded and appropriate content. In this research we used OpenAI GPT as point of comparison since it excels at all levels of safety. On the open-source side for smaller models Meta Llama2 performs well at factuality and toxicity but has the highest propensity for hallucination. Mistral hallucinates the least but cannot handle toxicity well. It performs well in a dataset mixing several tasks and safety vectors in a narrow vertical domain. Gemma the newly introduced open-source model based on Google Gemini is generally balanced but trailing behind. When engaging in back-and-forth conversation (multi-turn prompts) we find that the safety of open-source models degrades significantly. Aside from OpenAIs GPT Mistral is the only model that still performed well in multi-turn tests.
