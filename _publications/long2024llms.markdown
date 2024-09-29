---
layout: publication
title: Llms Are Biased Towards Output Formats! Systematically Evaluating And Mitigating Output Format Bias Of Llms
authors: Long Do Xuan, Ngoc Hai Nguyen, Sim Tiviatis, Dao Hieu, Joty Shafiq, Kawaguchi Kenji, Chen Nancy F., Kan Min-yen
conference: "Arxiv"
year: 2024
bibkey: long2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08656"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting']
---
We present the first systematic evaluation examining format bias in performance of large language models (LLMs). Our approach distinguishes between two categories of an evaluation metric under format constraints to reliably and accurately assess performance one measures performance when format constraints are adhered to while the other evaluates performance regardless of constraint adherence. We then define a metric for measuring the format bias of LLMs and establish effective strategies to reduce it. Subsequently we present our empirical format bias evaluation spanning four commonly used categories 45;45; multiple45;choice question45;answer wrapping list and mapping 45;45; covering 15 widely45;used formats. Our evaluation on eight generation tasks uncovers significant format bias across state45;of45;the45;art LLMs. We further discover that improving the format45;instruction following capabilities of LLMs across formats potentially reduces format bias. Based on our evaluation findings we study prompting and fine45;tuning with synthesized format data techniques to mitigate format bias. Our methods successfully reduce the variance in ChatGPTs performance among wrapping formats from 235.33 to 0.71 (37;^2).
