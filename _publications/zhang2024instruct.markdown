---
layout: publication
title: 'Instruct Or Interact? Exploring And Eliciting Llms'' Capability In Code Snippet Adaptation Through Prompt Engineering'
authors: Tanghaoran Zhang, Yue Yu, Xinjun Mao, Shangwen Wang, Kang Yang, Yao Lu, Zhang Zhang, Yuxin Zhao
conference: "Arxiv"
year: 2024
bibkey: zhang2024instruct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15501"}
tags: ['Prompting', 'Agentic', 'Applications', 'Reinforcement Learning']
---
Code snippet adaptation is a fundamental activity in the software development
process. Unlike code generation, code snippet adaptation is not a "free
creation", which requires developers to tailor a given code snippet in order to
fit specific requirements and the code context. Recently, large language models
(LLMs) have confirmed their effectiveness in the code generation task with
promising results. However, their performance on adaptation, a reuse-oriented
and context-dependent code change prediction task, is still unclear. To bridge
this gap, we conduct an empirical study to investigate the performance and
issues of LLMs on the adaptation task. We first evaluate the adaptation
performances of three popular LLMs and compare them to the code generation
task. Our result indicates that their adaptation ability is weaker than
generation, with a nearly 15% decrease on pass@1 and more context-related
errors. By manually inspecting 200 cases, we further investigate the causes of
LLMs' sub-optimal performance, which can be classified into three categories,
i.e., Unclear Requirement, Requirement Misalignment and Context Misapplication.
Based on the above empirical research, we propose an interactive prompting
approach to eliciting LLMs' adaptation ability. Experimental result reveals
that our approach greatly improve LLMs' adaptation performance. The
best-performing Human-LLM interaction successfully solves 159 out of the 202
identified defects and improves the pass@1 and pass@5 by over 40% compared to
the initial instruction-based prompt. Considering human efforts, we suggest
multi-agent interaction as a trade-off, which can achieve comparable
performance with excellent generalization ability. We deem that our approach
could provide methodological assistance for autonomous code snippet reuse and
adaptation with LLMs.
