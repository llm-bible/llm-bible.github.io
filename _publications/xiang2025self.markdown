---
layout: publication
title: 'Self-supervised Prompt Optimization'
authors: Jinyu Xiang, Jiayi Zhang, Zhaoyang Yu, Fengwei Teng, Jinhao Tu, Xinbing Liang, Sirui Hong, Chenglin Wu, Yuyu Luo
conference: "Arxiv"
year: 2025
bibkey: xiang2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06855"}
  - {name: "Code", url: "https://github.com/geekan/MetaGPT/blob/main/examples/spo"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Prompting']
---
Well-designed prompts are crucial for enhancing Large language models' (LLMs)
reasoning capabilities while aligning their outputs with task requirements
across diverse domains. However, manually designed prompts require expertise
and iterative experimentation. While existing prompt optimization methods aim
to automate this process, they rely heavily on external references such as
ground truth or by humans, limiting their applicability in real-world scenarios
where such data is unavailable or costly to obtain. To address this, we propose
Self-Supervised Prompt Optimization (SPO), a cost-efficient framework that
discovers effective prompts for both closed and open-ended tasks without
requiring external reference. Motivated by the observations that prompt quality
manifests directly in LLM outputs and LLMs can effectively assess adherence to
task requirements, we derive evaluation and optimization signals purely from
output comparisons. Specifically, SPO selects superior prompts through pairwise
output comparisons evaluated by an LLM evaluator, followed by an LLM optimizer
that aligns outputs with task requirements. Extensive experiments demonstrate
that SPO outperforms state-of-the-art prompt optimization methods, achieving
comparable or superior results with significantly lower costs (e.g., 1.1% to
5.6% of existing methods) and fewer samples (e.g., three samples). The code is
available at https://github.com/geekan/MetaGPT/blob/main/examples/spo
