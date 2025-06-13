---
layout: publication
title: 'A Deep Dive Into Large Language Model Code Generation Mistakes: What And Why?'
authors: Qihong Chen, Jiachen Yu, Jiawei Li, Jiecheng Deng, Justin Tian Jin Chen, Iftekhar Ahmed
conference: "Arxiv"
year: 2024
bibkey: chen2024deep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01414"}
tags: ['GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Prompting']
---
Recent advancements in Large Language Models (LLMs) have led to their
widespread application in automated code generation. However, these models can
still generate defective code that deviates from the specification. Previous
research has mainly focused on the mistakes in LLM-generated standalone
functions, overlooking real-world software development situations where the
successful generation of the code requires software contexts such as external
dependencies. In this paper, we considered both of these code generation
situations and identified a range of \textit\{non-syntactic mistakes\} arising
from LLMs' misunderstandings of coding question specifications. Seven
categories of non-syntactic mistakes were identified through extensive manual
analyses, four of which were missed by previous works. To better understand
these mistakes, we proposed six reasons behind these mistakes from various
perspectives. Moreover, we explored the effectiveness of LLMs in detecting
mistakes and their reasons. Our evaluation demonstrated that GPT-4 with the
ReAct prompting technique can achieve an F1 score of up to 0.65 when
identifying reasons for LLM's mistakes, such as misleading function signatures.
We believe that these findings offer valuable insights into enhancing the
quality of LLM-generated code.
