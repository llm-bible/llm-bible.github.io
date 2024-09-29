---
layout: publication
title: Socreval Large Language Models With The Socratic Method For Reference-free Reasoning Evaluation
authors: He Hangfeng, Zhang Hongming, Roth Dan
conference: "Arxiv"
year: 2023
bibkey: he2023socreval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00074"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
To comprehensively gauge the capacity of current models for complex reasoning it is crucial to assess their step-by-step reasoning in a scalable manner. Established reference-based evaluation metrics rely on human-annotated reasoning chains as references to assess the model-derived chains. However such gold-standard human-written reasoning chains may not be unique and their acquisition is often labor-intensive. Existing reference-free reasoning evaluation metrics while eliminating the need for human-crafted reasoning chains as references often require fine-tuning with human-derived chains before evaluation complicating the process and questioning their adaptability to other datasets. To address these challenges we harness GPT-4 to automatically evaluate reasoning chain quality thereby removing the dependency on human-written reasoning chains for both model fine-tuning and evaluative purposes. Leveraging the Socratic method we develop SocREval (bf Socratic Method-Inspired bf Reasoning bf Evaluation) a novel approach for prompt design in reference-free reasoning evaluation. Empirical results from four human annotated datasets reveal that SocREval significantly improves GPT-4s performance surpassing existing reference-free and reference-based reasoning evaluation metrics. Beyond its demonstrated efficacy SocREval proves to be both cost-efficient and robust to prompt writing and example selection as substantiated by our in-depth analysis.
