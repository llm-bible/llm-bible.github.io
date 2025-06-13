---
layout: publication
title: 'Mathcamps: Fine-grained Synthesis Of Mathematical Problems From Human Curricula'
authors: Shubhra Mishra, Gabriel Poesia, Belinda Mo, Noah D. Goodman
conference: "Arxiv"
year: 2024
bibkey: mishra2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00900"}
tags: ['Security', 'Training Techniques', 'Tools']
---
Mathematical problem solving is an important skill for Large Language Models
(LLMs), both as an important capability and a proxy for a range of reasoning
abilities. Existing benchmarks probe a diverse set of skills, but they yield
aggregate accuracy metrics, obscuring specific abilities or weaknesses.
Furthermore, they are difficult to extend with new problems, risking data
contamination over time. To address these challenges, we propose MathCAMPS: a
method to synthesize high-quality mathematical problems at scale, grounded on
44 fine-grained "standards" from the Mathematics Common Core (CC) Standard for
K-8 grades. We encode each standard in a formal grammar, allowing us to sample
diverse symbolic problems and their answers. We then use LLMs to realize the
symbolic problems into word problems. We propose a cycle-consistency method for
validating problem faithfulness. Finally, we derive follow-up questions from
symbolic structures and convert them into follow-up word problems - a novel
task of mathematical dialogue that probes for robustness in understanding.
Experiments on 23 LLMs show surprising failures even in the strongest models
(in particular when asked simple follow-up questions). Moreover, we evaluate
training checkpoints of Pythia 12B on MathCAMPS, allowing us to analyze when
particular mathematical skills develop during its training. Our framework
enables the community to reproduce and extend our pipeline for a fraction of
the typical cost of building new high-quality datasets.
