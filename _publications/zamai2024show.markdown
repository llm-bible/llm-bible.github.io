---
layout: publication
title: 'Show Less, Instruct More: Enriching Prompts With Definitions And Guidelines For Zero-shot NER'
authors: Andrew Zamai, Andrea Zugarini, Leonardo Rigutini, Marco Ernandes, Marco Maggini
conference: "Arxiv"
year: 2024
bibkey: zamai2024show
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01272"}
tags: ['Fine-Tuning', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Recently, several specialized instruction-tuned Large Language Models (LLMs)
for Named Entity Recognition (NER) have emerged. Compared to traditional NER
approaches, these models have demonstrated strong generalization capabilities.
Existing LLMs primarily focus on addressing zero-shot NER on Out-of-Domain
inputs, while fine-tuning on an extensive number of entity classes that often
highly or completely overlap with test sets. In this work instead, we propose
SLIMER, an approach designed to tackle never-seen-before entity tags by
instructing the model on fewer examples, and by leveraging a prompt enriched
with definition and guidelines. Experiments demonstrate that definition and
guidelines yield better performance, faster and more robust learning,
particularly when labelling unseen named entities. Furthermore, SLIMER performs
comparably to state-of-the-art approaches in out-of-domain zero-shot NER, while
being trained in a more fair, though certainly more challenging, setting.
