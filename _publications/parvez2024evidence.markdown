---
layout: publication
title: 'Evidence To Generate (E2G): A Single-agent Two-step Prompting For Context Grounded And Retrieval Augmented Reasoning'
authors: Parvez Md Rizwan
conference: "Arxiv"
year: 2024
bibkey: parvez2024evidence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05787"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
While chain-of-thought (CoT) prompting has revolutionized how LLMs perform reasoning tasks, its current methods and variations (e.g, Self-consistency, ReACT, Reflexion, Tree-of-Thoughts (ToT), Cumulative Reasoning (CR)) suffer from limitations like slowness, limited context grounding, hallucination and inconsistent outputs. To overcome these challenges, we introduce Evidence to Generate (E2G), a novel single-agent, two-step prompting framework. Instead of unverified reasoning claims, this innovative approach leverages the power of evidence for decision making by first focusing exclusively on the thought sequences (the series of intermediate steps) explicitly mentioned in the context which then serve as extracted evidence, guiding the LLM's output generation process with greater precision and efficiency. This simple yet powerful approach unlocks the true potential of chain-of-thought like prompting, paving the way for faster, more reliable, and more contextually aware reasoning in LLMs. \tool achieves remarkable results robustly across a wide range of knowledge-intensive reasoning and generation tasks, surpassing baseline approaches with state-of-the-art LLMs. For example, (i) on LogiQA benchmark using GPT-4 as backbone model, \tool achieves a new state-of-the Accuracy of 53.8&#37; exceeding CoT by 18&#37;, ToT by 11&#37;, CR by 9&#37; (ii) a variant of E2G with PaLM2 outperforms the variable-shot performance of Gemini Ultra by 0.9 F1 points, reaching an F1 score of 83.3 on a subset of DROP.
