---
layout: publication
title: 'Symbolic Mixture-of-experts: Adaptive Skill-based Routing For Heterogeneous Reasoning'
authors: Justin Chih-yao Chen, Sukwon Yun, Elias Stengel-eskin, Tianlong Chen, Mohit Bansal
conference: "Arxiv"
year: 2025
bibkey: chen2025symbolic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.05641'}
tags: ['Agentic', 'RAG', 'Model Architecture', 'GPT', 'Tools']
---
Combining existing pre-trained expert LLMs is a promising avenue for scalably
tackling large-scale and diverse tasks. However, selecting experts at the task
level is often too coarse-grained, as heterogeneous tasks may require different
expertise for each instance. To enable adaptive instance-level mixing of
pre-trained LLM experts, we propose Symbolic-MoE, a symbolic, text-based, and
gradient-free Mixture-of-Experts framework. Symbolic-MoE takes a fine-grained
approach to selection by emphasizing skills, e.g., algebra in math or molecular
biology in biomedical reasoning. We propose a skill-based recruiting strategy
that dynamically selects the most relevant set of expert LLMs for diverse
reasoning tasks based on their strengths. Each selected expert then generates
its own reasoning, resulting in k outputs from k experts, which are then
synthesized into a final high-quality response by an aggregator chosen based on
its ability to integrate diverse reasoning outputs. We show that Symbolic-MoE's
instance-level expert selection improves performance by a large margin but --
when implemented naively -- can introduce a high computational overhead due to
the need for constant model loading and offloading. To address this, we
implement a batch inference strategy that groups instances based on their
assigned experts, loading each model only once. This allows us to integrate 16
expert models on 1 GPU with a time cost comparable to or better than prior
multi-agent baselines using 4 GPUs. Through extensive evaluations on diverse
benchmarks (MMLU-Pro, GPQA, AIME, and MedMCQA), we demonstrate that
Symbolic-MoE outperforms strong LLMs like GPT4o-mini, as well as multi-agent
approaches, with an absolute average improvement of 8.15% over the best
multi-agent baseline. Moreover, Symbolic-MoE removes the need for expensive
multi-round discussions, outperforming discussion baselines with less
computation.
