---
layout: publication
title: 'Chain Of Evidences And Evidence To Generate: Prompting For Context Grounded And Retrieval Augmented Reasoning'
authors: Md Rizwan Parvez
conference: "Arxiv"
year: 2024
bibkey: parvez2024chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05787"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Interpretability', 'Prompting']
---
While chain-of-thoughts (CoT) prompting has revolutionized how LLMs perform
reasoning tasks, its current methods and variations (e.g, Self-consistency,
ReACT, Reflexion, Tree-of-Thoughts (ToT), Cumulative Reasoning (CR) etc.,)
suffer from limitations like limited context grounding,
hallucination/inconsistent output generation, and iterative sluggishness. To
overcome these challenges, we introduce a novel mono/dual-step zero-shot
prompting framework built upon two unique strategies Chain of Evidences (CoE)\}
and Evidence to Generate (E2G). Instead of unverified reasoning claims, our
innovative approaches leverage the power of "evidence for decision making" by
first focusing exclusively on the thought sequences explicitly mentioned in the
context which then serve as extracted evidence, guiding the LLM's output
generation process with greater precision and efficiency. This simple yet
potent approach unlocks the full potential of chain-of-thoughts prompting,
facilitating faster, more reliable, and contextually aware reasoning in LLMs.
Our framework consistently achieves remarkable results across various
knowledge-intensive reasoning and generation tasks, surpassing baseline
approaches with state-of-the-art LLMs. For instance, (i) on the LogiQA
benchmark using GPT-4, CoE achieves a new state-of-the-art accuracy of 53.8%,
surpassing CoT by 18%, ToT by 11%, and CR by 9%; (ii) CoE with PaLM-2
outperforms the variable-shot performance of Gemini Ultra by 0.9 F1 points,
achieving an F1 score of 83.3 on DROP. We release our prompts and outputs on
these benchmarks as a new instruction tuning dataset for future research at
https://huggingface.co/datasets/kagnlp/Chain-of-Evidences/.
