---
layout: publication
title: 'The Geometry Of Truth: Emergent Linear Structure In Large Language Model Representations Of True/false Datasets'
authors: Marks Samuel, Tegmark Max
conference: "Arxiv"
year: 2023
bibkey: marks2023geometry
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06824"}
tags: ['Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have impressive capabilities, but are prone to outputting falsehoods. Recent work has developed techniques for inferring whether a LLM is telling the truth by training probes on the LLM's internal activations. However, this line of work is controversial, with some authors pointing out failures of these probes to generalize in basic ways, among other conceptual issues. In this work, we use high-quality datasets of simple true/false statements to study in detail the structure of LLM representations of truth, drawing on three lines of evidence: 1. Visualizations of LLM true/false statement representations, which reveal clear linear structure. 2. Transfer experiments in which probes trained on one dataset generalize to different datasets. 3. Causal evidence obtained by surgically intervening in a LLM's forward pass, causing it to treat false statements as true and vice versa. Overall, we present evidence that at sufficient scale, LLMs linearly represent the truth or falsehood of factual statements. We also show that simple difference-in-mean probes generalize as well as other probing techniques while identifying directions which are more causally implicated in model outputs.
