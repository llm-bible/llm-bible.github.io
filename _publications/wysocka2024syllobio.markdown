---
layout: publication
title: 'Syllobio-nli: Evaluating Large Language Models On Biomedical Syllogistic Reasoning'
authors: Magdalena Wysocka, Danilo Carvalho, Oskar Wysocki, Marco Valentino, Andre Freitas
conference: "Arxiv"
year: 2024
bibkey: wysocka2024syllobio
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14399"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Pre-Training', 'Applications', 'In-Context Learning']
---
Syllogistic reasoning is crucial for Natural Language Inference (NLI). This
capability is particularly significant in specialized domains such as
biomedicine, where it can support automatic evidence interpretation and
scientific discovery. This paper presents SylloBio-NLI, a novel framework that
leverages external ontologies to systematically instantiate diverse syllogistic
arguments for biomedical NLI. We employ SylloBio-NLI to evaluate Large Language
Models (LLMs) on identifying valid conclusions and extracting supporting
evidence across 28 syllogistic schemes instantiated with human genome pathways.
Extensive experiments reveal that biomedical syllogistic reasoning is
particularly challenging for zero-shot LLMs, which achieve an average accuracy
between 70% on generalized modus ponens and 23% on disjunctive syllogism. At
the same time, we found that few-shot prompting can boost the performance of
different LLMs, including Gemma (+14%) and LLama-3 (+43%). However, a deeper
analysis shows that both techniques exhibit high sensitivity to superficial
lexical variations, highlighting a dependency between reliability, models'
architecture, and pre-training regime. Overall, our results indicate that,
while in-context examples have the potential to elicit syllogistic reasoning in
LLMs, existing models are still far from achieving the robustness and
consistency required for safe biomedical NLI applications.
