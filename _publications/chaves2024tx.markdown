---
layout: publication
title: 'Tx-llm: A Large Language Model For Therapeutics'
authors: Juan Manuel Zambrano Chaves, Eric Wang, Tao Tu, Eeshit Dhaval Vaishnav, Byron Lee, S. Sara Mahdavi, Christopher Semturs, David Fleet, Vivek Natarajan, Shekoofeh Azizi
conference: "Arxiv"
year: 2024
bibkey: chaves2024tx
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.06316'}
tags: ['RAG', 'Training Techniques', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Developing therapeutics is a lengthy and expensive process that requires the
satisfaction of many different criteria, and AI models capable of expediting
the process would be invaluable. However, the majority of current AI approaches
address only a narrowly defined set of tasks, often circumscribed within a
particular domain. To bridge this gap, we introduce Tx-LLM, a generalist large
language model (LLM) fine-tuned from PaLM-2 which encodes knowledge about
diverse therapeutic modalities. Tx-LLM is trained using a collection of 709
datasets that target 66 tasks spanning various stages of the drug discovery
pipeline. Using a single set of weights, Tx-LLM simultaneously processes a wide
variety of chemical or biological entities(small molecules, proteins, nucleic
acids, cell lines, diseases) interleaved with free-text, allowing it to predict
a broad range of associated properties, achieving competitive with
state-of-the-art (SOTA) performance on 43 out of 66 tasks and exceeding SOTA on
22. Among these, Tx-LLM is particularly powerful and exceeds best-in-class
performance on average for tasks combining molecular SMILES representations
with text such as cell line names or disease names, likely due to context
learned during pretraining. We observe evidence of positive transfer between
tasks with diverse drug types (e.g.,tasks involving small molecules and tasks
involving proteins), and we study the impact of model size, domain finetuning,
and prompting strategies on performance. We believe Tx-LLM represents an
important step towards LLMs encoding biochemical knowledge and could have a
future role as an end-to-end tool across the drug discovery development
pipeline.
