---
layout: publication
title: 'Instruct-of-reflection: Enhancing Large Language Models Iterative Reflection Capabilities Via Dynamic-meta Instruction'
authors: Liping Liu, Chunhong Zhang, Likang Wu, Chuang Zhao, Zheng Hu, Ming He, Jianping Fan
conference: "Arxiv"
year: 2025
bibkey: liu2025instruct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00902"}
tags: ['RAG', 'Model Architecture', 'Attention Mechanism', 'Tools']
---
Self-reflection for Large Language Models (LLMs) has gained significant
attention. Existing approaches involve models iterating and improving their
previous responses based on LLMs' internal reflection ability or external
feedback. However, recent research has raised doubts about whether intrinsic
self-correction without external feedback may even degrade performance. Based
on our empirical evidence, we find that current static reflection methods may
lead to redundant, drift, and stubborn issues. To mitigate this, we introduce
Instruct-of-Reflection (IoRT), a novel and general reflection framework that
leverages dynamic-meta instruction to enhance the iterative reflection
capability of LLMs. Specifically, we propose the instructor driven by the
meta-thoughts and self-consistency classifier, generates various instructions,
including refresh, stop, and select, to guide the next reflection iteration.
Our experiments demonstrate that IoRT achieves an average improvement of 10.1%
over established baselines in mathematical and commonsense reasoning tasks,
highlighting its efficacy and applicability.
