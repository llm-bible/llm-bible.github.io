---
layout: publication
title: 'Compassjudger-1: All-in-one Judge Model Helps Model Evaluation And Evolution'
authors: Maosong Cao, Alexander Lam, Haodong Duan, Hongwei Liu, Songyang Zhang, Kai Chen
conference: "Arxiv"
year: 2024
bibkey: cao2024compassjudger
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16256"}
  - {name: "Code", url: "https://github.com/open-compass/CompassJudger"}
tags: ['Tools', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Has Code']
---
Efficient and accurate evaluation is crucial for the continuous improvement
of large language models (LLMs). Among various assessment methods, subjective
evaluation has garnered significant attention due to its superior alignment
with real-world usage scenarios and human preferences. However, human-based
evaluations are costly and lack reproducibility, making precise automated
evaluators (judgers) vital in this process. In this report, we introduce
\textbf\{CompassJudger-1\}, the first open-source \textbf\{all-in-one\} judge LLM.
CompassJudger-1 is a general-purpose LLM that demonstrates remarkable
versatility. It is capable of: 1. Performing unitary scoring and two-model
comparisons as a reward model; 2. Conducting evaluations according to specified
formats; 3. Generating critiques; 4. Executing diverse tasks like a general
LLM. To assess the evaluation capabilities of different judge models under a
unified setting, we have also established \textbf\{JudgerBench\}, a new benchmark
that encompasses various subjective evaluation tasks and covers a wide range of
topics. CompassJudger-1 offers a comprehensive solution for various evaluation
tasks while maintaining the flexibility to adapt to diverse requirements. Both
CompassJudger and JudgerBench are released and available to the research
community athttps://github.com/open-compass/CompassJudger. We believe that by
open-sourcing these tools, we can foster collaboration and accelerate progress
in LLM evaluation methodologies.
