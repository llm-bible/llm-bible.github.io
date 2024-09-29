---
layout: publication
title: 'Understanding Information Storage And Transfer In Multi-modal Large Language Models'
authors: Basu Samyadeep, Grayson Martin, Morrison Cecily, Nushi Besmira, Feizi Soheil, Massiceti Daniela
conference: "Arxiv"
year: 2024
bibkey: basu2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04236"}
tags: ['Applications', 'Attention Mechanism', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Understanding the mechanisms of information storage and transfer in Transformer-based models is important for driving model understanding progress. Recent work has studied these mechanisms for Large Language Models (LLMs) revealing insights on how information is stored in a models parameters and how information flows to and from these parameters in response to specific prompts. However these studies have not yet been extended to Multi-modal Large Language Models (MLLMs). Given their expanding capabilities and real-world use we start by studying one aspect of these models -- how MLLMs process information in a factual visual question answering task. We use a constraint-based formulation which views a visual question as having a set of visual or textual constraints that the models generated answer must satisfy to be correct (e.g. What movie directed by the director in this photo has won a Golden Globe). Under this setting we contribute i) a method that extends causal information tracing from pure language to the multi-modal setting and ii) VQA-Constraints a test-bed of 9.7K visual questions annotated with constraints. We use these tools to study two open-source MLLMs LLaVa and multi-modal Phi-2. Our key findings show that these MLLMs rely on MLP and self-attention blocks in much earlier layers for information storage compared to LLMs whose mid-layer MLPs are more important. We also show that a consistent small subset of visual tokens output by the vision encoder are responsible for transferring information from the image to these causal blocks. We validate these mechanisms by introducing MultEdit a model-editing algorithm that can correct errors and insert new long-tailed information into MLLMs by targeting these causal blocks.
