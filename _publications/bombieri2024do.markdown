---
layout: publication
title: 'Do Llms Dream Of Ontologies?'
authors: Marco Bombieri, Paolo Fiorini, Simone Paolo Ponzetto, Marco Rospocher
conference: "Arxiv"
year: 2024
bibkey: bombieri2024do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.14931"}
tags: ['Prompting', 'Security', 'Model Architecture', 'GPT']
---
Large Language Models (LLMs) have demonstrated remarkable performance across
diverse natural language processing tasks, yet their ability to memorize
structured knowledge remains underexplored. In this paper, we investigate the
extent to which general-purpose pre-trained LLMs retain and correctly reproduce
concept identifier (ID)-label associations from publicly available ontologies.
We conduct a systematic evaluation across multiple ontological resources,
including the Gene Ontology, Uberon, Wikidata, and ICD-10, using LLMs such as
Pythia-12B, Gemini-1.5-Flash, GPT-3.5, and GPT-4. Our findings reveal that only
a small fraction of ontological concepts is accurately memorized, with GPT-4
demonstrating the highest performance. To understand why certain concepts are
memorized more effectively than others, we analyze the relationship between
memorization accuracy and concept popularity on the Web. Our results indicate a
strong correlation between the frequency of a concept's occurrence online and
the likelihood of accurately retrieving its ID from the label. This suggests
that LLMs primarily acquire such knowledge through indirect textual exposure
rather than directly from structured ontological resources. Furthermore, we
introduce new metrics to quantify prediction invariance, demonstrating that the
stability of model responses across variations in prompt language and
temperature settings can serve as a proxy for estimating memorization
robustness.
