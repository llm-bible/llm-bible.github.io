---
layout: publication
title: 'Debunc: Mitigating Hallucinations In Large Language Model Agent Communication With Uncertainty Estimations'
authors: Yoffe Luke, Amayuelas Alfonso, Wang William Yang
conference: "Arxiv"
year: 2024
bibkey: yoffe2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06426"}
  - {name: "Code", url: "https://github.com/lukeyoffe/debunc"}
tags: ['Agentic', 'Attention Mechanism', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools', 'Transformer']
---
To enhance Large Language Model (LLM) capabilities, multi-agent debates have been introduced, where multiple LLMs discuss solutions to a problem over several rounds of debate. However, LLMs often produce incorrect responses that appear deceptively confident, which can mislead other agents. This is partly because agents do not express their confidence levels during standard debates. To address this, we introduce DebUnc, a multi-agent debate framework that uses uncertainty metrics to assess agent confidence levels. We adapted the LLM attention mechanism to adjust token weights based on confidence levels and also explored using textual prompts to convey confidence. Our evaluations across various benchmarks show that attention-based methods are particularly effective, and that as uncertainty metrics evolve, performance will continue to increase. The code is available at https://github.com/lukeyoffe/debunc
