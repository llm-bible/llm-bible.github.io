---
layout: publication
title: Detecting Hallucination And Coverage Errors In Retrieval Augmented Generation For Controversial Topics
authors: Chang Tyler A., Tomanek Katrin, Hoffmann Jessica, Thain Nithum, Van Liemt Erin, Meier-hellstern Kathleen, Dixon Lucas
conference: "Arxiv"
year: 2024
bibkey: chang2024detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.08904"}
tags: ['Applications', 'Language Modeling', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
We explore a strategy to handle controversial topics in LLM45;based chatbots based on Wikipedias Neutral Point of View (NPOV) principle acknowledge the absence of a single true answer and surface multiple perspectives. We frame this as retrieval augmented generation where perspectives are retrieved from a knowledge base and the LLM is tasked with generating a fluent and faithful response from the given perspectives. As a starting point we use a deterministic retrieval system and then focus on common LLM failure modes that arise during this approach to text generation namely hallucination and coverage errors. We propose and evaluate three methods to detect such errors based on (1) word45;overlap (2) salience and (3) LLM45;based classifiers. Our results demonstrate that LLM45;based classifiers even when trained only on synthetic errors achieve high error detection performance with ROC AUC scores of 95.337; for hallucination and 90.537; for coverage error detection on unambiguous error cases. We show that when no training data is available our other methods still yield good results on hallucination (84.037;) and coverage error (85.237;) detection.
