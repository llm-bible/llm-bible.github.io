---
layout: publication
title: 'On The Intrinsic Self-correction Capability Of Llms: Uncertainty And Latent Concept'
authors: Guangliang Liu, Haitao Mao, Bochuan Cao, Zhiyu Xue, Xitong Zhang, Rongrong Wang, Jiliang Tang, Kristen Johnson
conference: "Arxiv"
year: 2024
bibkey: liu2024intrinsic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02378"}
tags: ['Applications', 'Reinforcement Learning']
---
Large Language Models (LLMs) are able to improve their responses when
instructed to do so, a capability known as self-correction. When instructions
provide only the task's goal without specific details about potential issues in
the response, LLMs must rely on their internal knowledge to improve response
quality, a process referred to as intrinsic self-correction. The empirical
success of intrinsic self-correction is evident in various applications, but
how and why it is effective remains unknown. In this paper, we unveil that
intrinsic self-correction can be progressively improved, allowing it to
approach a converged state. Our findings are verified in: (1) the scenario of
multi-round question answering, by comprehensively demonstrating that intrinsic
self-correction can progressively introduce performance gains through iterative
interactions, ultimately converging to stable performance; and (2) the context
of intrinsic self-correction for enhanced morality, in which we provide
empirical evidence that iteratively applying instructions reduces model
uncertainty towards convergence, which then leads to convergence of both the
calibration error and self-correction performance, ultimately resulting in a
stable state of intrinsic self-correction. Furthermore, we introduce a
mathematical formulation and a simulation task indicating that the latent
concepts activated by self-correction instructions drive the reduction of model
uncertainty. Based on our experimental results and analysis of the convergence
of intrinsic self-correction, we reveal its underlying mechanism: consistent
injected instructions reduce model uncertainty which yields converged, improved
performance.
