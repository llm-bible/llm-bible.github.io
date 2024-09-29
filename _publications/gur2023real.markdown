---
layout: publication
title: "A Real-world Webagent With Planning, Long Context Understanding, And Program Synthesis"
authors: Gur Izzeddin, Furuta Hiroki, Huang Austin, Safdari Mustafa, Matsuo Yutaka, Eck Douglas, Faust Aleksandra
conference: "Arxiv"
year: 2023
bibkey: gur2023real
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.12856"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Ethics And Bias', 'Model Architecture', 'Reinforcement Learning', 'Transformer']
---
Pre-trained large language models (LLMs) have recently achieved better generalization and sample efficiency in autonomous web automation. However the performance on real-world websites has still suffered from (1) open domainness (2) limited context length and (3) lack of inductive bias on HTML. We introduce WebAgent an LLM-driven agent that learns from self-experience to complete tasks on real websites following natural language instructions. WebAgent plans ahead by decomposing instructions into canonical sub-instructions summarizes long HTML documents into task-relevant snippets and acts on websites via Python programs generated from those. We design WebAgent with Flan-U-PaLM for grounded code generation and HTML-T5 new pre-trained LLMs for long HTML documents using local and global attention mechanisms and a mixture of long-span denoising objectives for planning and summarization. We empirically demonstrate that our modular recipe improves the success on real websites by over 5037; and that HTML-T5 is the best model to solve various HTML understanding tasks; achieving 18.737; higher success rate than the prior method on MiniWoB web automation benchmark and SoTA performance on Mind2Web an offline task planning evaluation.
