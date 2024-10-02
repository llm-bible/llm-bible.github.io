---
layout: publication
title: 'Llms Are Biased Towards Output Formats! Systematically Evaluating And Mitigating Output Format Bias Of Llms'
authors: Long Do Xuan, Ngoc Hai Nguyen, Sim Tiviatis, Dao Hieu, Joty Shafiq, Kawaguchi Kenji, Chen Nancy F., Kan Min-yen
conference: "Arxiv"
year: 2024
bibkey: long2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08656"}
tags: ['Ethics And Bias', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
'We present the first systematic evaluation examining format bias in performance of large language models (LLMs). Our approach distinguishes between two categories of an evaluation metric under format constraints to reliably and accurately assess performance: one measures performance when format constraints are adhered to, while the other evaluates performance regardless of constraint adherence. We then define a metric for measuring the format bias of LLMs and establish effective strategies to reduce it. Subsequently, we present our empirical format bias evaluation spanning four commonly used categories -- multiple-choice question-answer, wrapping, list, and mapping -- covering 15 widely-used formats. Our evaluation on eight generation tasks uncovers significant format bias across state-of-the-art LLMs. We further discover that improving the format-instruction following capabilities of LLMs across formats potentially reduces format bias. Based on our evaluation findings, we study prompting and fine-tuning with synthesized format data techniques to mitigate format bias. Our methods successfully reduce the variance in ChatGPT''s performance among wrapping formats from 235.33 to 0.71 (&#37;\(^2\)).'
