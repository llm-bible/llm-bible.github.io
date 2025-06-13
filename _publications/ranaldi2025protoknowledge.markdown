---
layout: publication
title: 'Protoknowledge Shapes Behaviour Of Llms In Downstream Tasks: Memorization And Generalization With Knowledge Graphs'
authors: Federico Ranaldi, Andrea Zugarini, Leonardo Ranaldi, Fabio Massimo Zanzotto
conference: "Arxiv"
year: 2025
bibkey: ranaldi2025protoknowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15501"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Ethics and Bias', 'Pretraining Methods', 'Prompting', 'Applications']
---
We introduce the concept of protoknowledge to formalize and measure how sequences of tokens encoding Knowledge Graphs are internalized during pretraining and utilized at inference time by Large Language Models (LLMs). Indeed, LLMs have demonstrated the ability to memorize vast amounts of token sequences during pretraining, and a central open question is how they leverage this memorization as reusable knowledge through generalization. We then categorize protoknowledge into lexical, hierarchical, and topological forms, varying on the type of knowledge that needs to be activated. We measure protoknowledge through Knowledge Activation Tasks (KATs), analyzing its general properties such as semantic bias. We then investigate the impact of protoknowledge on Text-to-SPARQL performance by varying prompting strategies depending on input conditions. To this end, we adopt a novel analysis framework that assesses whether model predictions align with the successful activation of the relevant protoknowledge for each query. This methodology provides a practical tool to explore Semantic-Level Data Contamination and serves as an effective strategy for Closed-Pretraining models.
