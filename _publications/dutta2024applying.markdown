---
layout: publication
title: Applying RLAIF for Code Generation with API-usage in Lightweight LLMs
authors: Dutta Sujan, Mahinder Sayantan, Anantha Raviteja, Bandyopadhyay Bortik
conference: "Arxiv"
year: 2024
bibkey: dutta2024applying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.20060"}
tags: ['ARXIV', 'Agentic', 'Applications', 'GPT', 'LLM', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
Reinforcement Learning from AI Feedback (RLAIF) has demonstrated significant potential across various domains including mitigating harm in LLM outputs enhancing text summarization and mathematical reasoning. This paper introduces an RLAIF framework for improving the code generation abilities of lightweight (<1B parameters) LLMs. We specifically focus on code generation tasks that require writing appropriate API calls which is challenging due to the well-known issue of hallucination in LLMs. Our framework extracts AI feedback from a larger LLM (e.g. GPT-3.5) through a specialized prompting strategy and uses this data to train a reward model towards better alignment from smaller LLMs. We run our experiments on the Gorilla dataset and meticulously assess the quality of the model-generated code across various metrics including AST ROUGE and Code-BLEU and develop a pipeline to compute its executability rate accurately. Our approach significantly enhances the fine-tuned LLM baselines performance achieving a 4.5 improvement in executability rate. Notably a smaller LLM model (780M parameters) trained with RLAIF surpasses a much larger fine-tuned baseline with 7B parameters achieving a 1.0 higher code executability rate.
