---
layout: publication
title: 'Accurate And Diverse LLM Mathematical Reasoning Via Automated Prm-guided Gflownets'
authors: Adam Younsi, Abdalgader Abubaker, Mohamed El Amine Seddik, Hakim Hacid, Salem Lahlou
conference: "Arxiv"
year: 2025
bibkey: younsi2025accurate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.19981"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning']
---
Achieving both accuracy and diverse reasoning remains challenging for Large
Language Models (LLMs) in complex domains like mathematics. A key bottleneck is
evaluating intermediate reasoning steps to guide generation without costly
human annotations. To address this, we first introduce a novel Process Reward
Model (PRM) trained automatically using Monte Carlo Tree Search coupled with a
similarity-based data augmentation technique, effectively capturing step-level
reasoning quality. Leveraging this PRM, we then adapt Generative Flow Networks
(GFlowNets) to operate at the reasoning step level. Unlike traditional
reinforcement learning focused on maximizing a single reward, GFlowNets
naturally sample diverse, high-quality solutions proportional to their rewards,
as measured by our PRM. Empirical evaluation shows strong improvements in both
accuracy and solution diversity on challenging mathematical benchmarks (e.g.,
+2.59% absolute accuracy on MATH Level 5 for Llama3.2-3B), with effective
generalization to unseen datasets (+9.4% absolute on SAT MATH). Our work
demonstrates the potential of PRM-guided, step-level GFlowNets for developing
more robust and versatile mathematical reasoning in LLMs.
