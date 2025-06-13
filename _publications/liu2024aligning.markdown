---
layout: publication
title: 'Aligning Teacher With Student Preferences For Tailored Training Data Generation'
authors: Yantao Liu, Zhao Zhang, Zijun Yao, Shulin Cao, Lei Hou, Juanzi Li
conference: "Arxiv"
year: 2024
bibkey: liu2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19227"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'In-Context Learning', 'Distillation', 'Fine-Tuning', 'Prompting', 'Attention Mechanism']
---
Large Language Models (LLMs) have shown significant promise as copilots in
various tasks. Local deployment of LLMs on edge devices is necessary when
handling privacy-sensitive data or latency-sensitive tasks. The computational
constraints of such devices make direct deployment of powerful large-scale LLMs
impractical, necessitating the Knowledge Distillation from large-scale models
to lightweight models. Lots of work has been done to elicit diversity and
quality training examples from LLMs, but little attention has been paid to
aligning teacher instructional content based on student preferences, akin to
"responsive teaching" in pedagogy. Thus, we propose ARTE, dubbed Aligning
TeacheR with StudenT PreferencEs, a framework that aligns the teacher model
with student preferences to generate tailored training examples for Knowledge
Distillation. Specifically, we elicit draft questions and rationales from the
teacher model, then collect student preferences on these questions and
rationales using students' performance with in-context learning as a proxy, and
finally align the teacher model with student preferences. In the end, we repeat
the first step with the aligned teacher model to elicit tailored training
examples for the student model on the target task. Extensive experiments on
academic benchmarks demonstrate the superiority of ARTE over existing
instruction-tuning datasets distilled from powerful LLMs. Moreover, we
thoroughly investigate the generalization of ARTE, including the generalization
of fine-tuned student models in reasoning ability and the generalization of
aligned teacher models to generate tailored training data across tasks and
students. In summary, our contributions lie in proposing a novel framework for
tailored training example generation, demonstrating its efficacy in
experiments, and investigating the generalization of both student & aligned
teacher models in ARTE.
