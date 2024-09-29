---
layout: publication
title: Strategic Chain-of-thought: Guiding Accurate Reasoning In Llms Through Strategy Elicitation
authors: Wang Yu, Zhao Shiwan, Wang Zhihu, Huang Heyuan, Fan Ming, Zhang Yubo, Wang Zhixing, Wang Haijun, Liu Ting
conference: "Arxiv"
year: 2024
bibkey: wang2024strategic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03271"}
tags: ['Applications', 'Few Shot', 'Prompting', 'Tools']
---
The Chain-of-Thought (CoT) paradigm has emerged as a critical approach for enhancing the reasoning capabilities of large language models (LLMs). However despite their widespread adoption and success CoT methods often exhibit instability due to their inability to consistently ensure the quality of generated reasoning paths leading to sub-optimal reasoning performance. To address this challenge we propose the (textbf)Strategic Chain-of-Thought (SCoT) a novel methodology designed to refine LLM performance by integrating strategic knowledge prior to generating intermediate reasoning steps. SCoT employs a two-stage approach within a single prompt first eliciting an effective problem-solving strategy which is then used to guide the generation of high-quality CoT paths and final answers. Our experiments across eight challenging reasoning datasets demonstrate significant improvements including a 21.0537; increase on the GSM8K dataset and 24.1337; on the Tracking_Objects dataset respectively using the Llama3-8b model. Additionally we extend the SCoT framework to develop a few-shot method with automatically matched demonstrations yielding even stronger results. These findings underscore the efficacy of SCoT highlighting its potential to substantially enhance LLM performance in complex reasoning tasks.
