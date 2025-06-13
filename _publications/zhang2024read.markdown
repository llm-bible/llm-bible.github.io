---
layout: publication
title: 'Read And Think: An Efficient Step-wise Multimodal Language Model For Document Understanding And Reasoning'
authors: Jinxu Zhang
conference: "Arxiv"
year: 2024
bibkey: zhang2024read
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.00816"}
tags: ['Multimodal Models', 'Few-Shot', 'RAG', 'Fine-Tuning', 'Interpretability and Explainability', 'Applications']
---
Understanding the contents of multimodal documents is essential to accurately
extract relevant evidence and use it for reasoning. Existing document
understanding models tend to generate answers with a single word or phrase
directly, ignoring the source document's evidence and lacking interpretability.
In this work, we address the lack of step-wise capabilities through data
augmentation and extension. Specifically, We use Multi-modal Large Language
Models (MLLMs), which have strong visual understanding and reasoning abilities,
as data generators to generate step-wise question-and-answer pairs for document
images and use a high-performance LLM as the error detector to filter out noisy
data. This step-wise data generation pipeline is implemented using both
template-based and few-shot methods. We then use the generated high-quality
data to train a humanized document understanding and reasoning model,
specifically designed to solve complex questions that require reasoning or
multi-hop question answering, dubbed DocAssistant. Experimental results
demonstrate the effectiveness and application value of step-wise generation,
showing a 5 improvement on InfoVQA with complex layouts and a 7 improvement on
ChartQA with complex reasoning, compared to directly generated answers. We hope
our work highlights the potential of synthetic data and encourages further
exploration of multi-modal document reasoning capabilities.
