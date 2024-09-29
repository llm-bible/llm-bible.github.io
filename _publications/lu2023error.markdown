---
layout: publication
title: Error Analysis Prompting Enables Human45;like Translation Evaluation In Large Language Models
authors: Lu Qingyu, Qiu Baopu, Ding Liang, Zhang Kanjian, Kocmi Tom, Tao Dacheng
conference: "Arxiv"
year: 2023
bibkey: lu2023error
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.13809"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Generative large language models (LLMs) e.g. ChatGPT have demonstrated remarkable proficiency across several NLP tasks such as machine translation text summarization. Recent research (Kocmi and Federmann 2023) has shown that utilizing LLMs for assessing the quality of machine translation (MT) achieves state45;of45;the45;art performance at the system level but textit123;performs poorly at the segment level125;. To further improve the performance of LLMs on MT quality assessment we investigate several prompting designs and propose a new prompting method called textbf123;texttt123;Error Analysis Prompting125;125; (EAPrompt) by combining Chain45;of45;Thoughts (Wei et al. 2022) and Error Analysis (Lu et al. 2023). This technique emulates the commonly accepted human evaluation framework 45; Multidimensional Quality Metrics (MQM Freitag et al. (2021)) and textit123;produces explainable and reliable MT evaluations at both the system and segment level125;. Experimental Results from the WMT22 metrics shared task validate the effectiveness of EAPrompt on various LLMs with different structures. Further analysis confirms that EAPrompt effectively distinguishes major errors from minor ones while also sharing a similar distribution of the number of errors with MQM. These findings highlight the potential of EAPrompt as a human45;like evaluator prompting technique for MT evaluation.
