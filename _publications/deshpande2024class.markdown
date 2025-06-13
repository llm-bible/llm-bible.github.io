---
layout: publication
title: 'Class-level Code Generation From Natural Language Using Iterative, Tool-enhanced Reasoning Over Repository'
authors: Ajinkya Deshpande, Anmol Agarwal, Shashank Shet, Arun Iyer, Aditya Kanade, Ramakrishna Bairi, Suresh Parthasarathy
conference: "Arxiv"
year: 2024
bibkey: deshpande2024class
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01573"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'RAG', 'Applications']
---
LLMs have demonstrated significant potential in code generation tasks,
achieving promising results at the function or statement level across various
benchmarks. However, the complexities associated with creating code artifacts
like classes, particularly within the context of real-world software
repositories, remain underexplored. Prior research treats class-level
generation as an isolated task, neglecting the intricate dependencies &
interactions that characterize real-world software environments. To address
this gap, we introduce RepoClassBench, a comprehensive benchmark designed to
rigorously evaluate LLMs in generating complex, class-level code within
real-world repositories. RepoClassBench includes "Natural Language to Class
generation" tasks across Java, Python & C# from a selection of repositories. We
ensure that each class in our dataset not only has cross-file dependencies
within the repository but also includes corresponding test cases to verify its
functionality. We find that current models struggle with the realistic
challenges posed by our benchmark, primarily due to their limited exposure to
relevant repository contexts. To address this shortcoming, we introduce
Retrieve-Repotools-Reflect (RRR), a novel approach that equips LLMs with static
analysis tools to iteratively navigate & reason about repository-level context
in an agent-based framework. Our experiments demonstrate that RRR significantly
outperforms existing baselines on RepoClassBench, showcasing its effectiveness
across programming languages & under various settings. Our findings emphasize
the critical need for code-generation benchmarks to incorporate repo-level
dependencies to more accurately reflect the complexities of software
development. Our work shows the benefits of leveraging specialized tools to
enhance LLMs' understanding of repository context. We plan to make our dataset
& evaluation harness public.
