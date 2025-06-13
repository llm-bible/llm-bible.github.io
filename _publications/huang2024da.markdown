---
layout: publication
title: 'Da-code: Agent Data Science Code Generation Benchmark For Large Language Models'
authors: Yiming Huang, Jianwen Luo, Yan Yu, Yitong Zhang, Fangyu Lei, Yifan Wei, Shizhu He, Lifu Huang, Xiao Liu, Jun Zhao, Kang Liu
conference: "Arxiv"
year: 2024
bibkey: huang2024da
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.07331"}
  - {name: "Code", url: "https://da-code-bench.github.io"}
tags: ['Agentic', 'Security', 'Tools', 'Reinforcement Learning', 'Has Code', 'Applications']
---
We introduce DA-Code, a code generation benchmark specifically designed to
assess LLMs on agent-based data science tasks. This benchmark features three
core elements: First, the tasks within DA-Code are inherently challenging,
setting them apart from traditional code generation tasks and demanding
advanced coding skills in grounding and planning. Second, examples in DA-Code
are all based on real and diverse data, covering a wide range of complex data
wrangling and analytics tasks. Third, to solve the tasks, the models must
utilize complex data science programming languages, to perform intricate data
processing and derive the answers. We set up the benchmark in a controllable
and executable environment that aligns with real-world data analysis scenarios
and is scalable. The annotators meticulously design the evaluation suite to
ensure the accuracy and robustness of the evaluation. We develop the DA-Agent
baseline. Experiments show that although the baseline performs better than
other existing frameworks, using the current best LLMs achieves only 30.5%
accuracy, leaving ample room for improvement. We release our benchmark at
https://da-code-bench.github.io.
