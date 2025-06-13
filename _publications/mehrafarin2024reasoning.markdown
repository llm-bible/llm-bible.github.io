---
layout: publication
title: 'Reasoning Or A Semblance Of It? A Diagnostic Study Of Transitive Reasoning In Llms'
authors: Houman Mehrafarin, Arash Eshghi, Ioannis Konstas
conference: "Arxiv"
year: 2024
bibkey: mehrafarin2024reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.20200"}
tags: ['Fine-Tuning', 'Pre-Training', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Evaluating Large Language Models (LLMs) on reasoning benchmarks demonstrates
their ability to solve compositional questions. However, little is known of
whether these models engage in genuine logical reasoning or simply rely on
implicit cues to generate answers. In this paper, we investigate the transitive
reasoning capabilities of two distinct LLM architectures, LLaMA 2 and Flan-T5,
by manipulating facts within two compositional datasets: QASC and Bamboogle. We
controlled for potential cues that might influence the models' performance,
including (a) word/phrase overlaps across sections of test input; (b) models'
inherent knowledge during pre-training or fine-tuning; and (c) Named Entities.
Our findings reveal that while both models leverage (a), Flan-T5 shows more
resilience to experiments (b and c), having less variance than LLaMA 2. This
suggests that models may develop an understanding of transitivity through
fine-tuning on knowingly relevant datasets, a hypothesis we leave to future
work.
