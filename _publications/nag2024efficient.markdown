---
layout: publication
title: 'Efficient Continual Pre-training Of Llms For Low-resource Languages'
authors: Arijit Nag, Soumen Chakrabarti, Animesh Mukherjee, Niloy Ganguly
conference: "Arxiv"
year: 2024
bibkey: nag2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10244"}
tags: ['Training Techniques', 'Pre-Training', 'Reinforcement Learning']
---
Open-source Large Language models (OsLLMs) propel the democratization of
natural language research by giving the flexibility to augment or update model
parameters for performance improvement. Nevertheless, like proprietary LLMs,
Os-LLMs offer poorer performance on low-resource languages (LRLs) than
high-resource languages (HRLs), owing to smaller amounts of training data and
underrepresented vocabulary. On the other hand, continual pre-training (CPT)
with large amounts of language-specific data is a costly proposition in terms
of data acquisition and computational resources. Our goal is to drastically
reduce CPT cost. To that end, we first develop a new algorithm to select a
subset of texts from a larger corpus. We show the effectiveness of our
technique using very little CPT data. In search of further improvement, we
design a new algorithm to select tokens to include in the LLM vocabulary. We
experiment with the recent Llama-3 model and nine Indian languages with diverse
scripts and extent of resource availability. For evaluation, we use
IndicGenBench, a generation task benchmark dataset for Indic languages. We
experiment with various CPT corpora and augmented vocabulary size and offer
insights across language families.
