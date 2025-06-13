---
layout: publication
title: 'Post-incorporating Code Structural Knowledge Into Llms Via In-context Learning For Code Translation'
authors: Yali Du, Hui Sun, Ming Li
conference: "Arxiv"
year: 2025
bibkey: du2025post
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22776"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Prompting', 'In-Context Learning']
---
Code translation migrates codebases across programming languages. Recently,
large language models (LLMs) have achieved significant advancements in software
mining. However, handling the syntactic structure of source code remains a
challenge. Classic syntax-aware methods depend on intricate model architectures
and loss functions, rendering their integration into LLM training
resource-intensive. This paper employs in-context learning (ICL), which
directly integrates task exemplars into the input context, to post-incorporate
code structural knowledge into pre-trained LLMs. We revisit exemplar selection
in ICL from an information-theoretic perspective, proposing that list-wise
selection based on information coverage is more precise and general objective
than traditional methods based on combining similarity and diversity. To
address the challenges of quantifying information coverage, we introduce a
surrogate measure, Coverage of Abstract Syntax Tree (CAST). Furthermore, we
formulate the NP-hard CAST maximization for exemplar selection and prove that
it is a standard submodular maximization problem. Therefore, we propose a
greedy algorithm for CAST submodular maximization, which theoretically
guarantees a (1-1/e)-approximate solution in polynomial time complexity. Our
method is the first training-free and model-agnostic approach to
post-incorporate code structural knowledge into existing LLMs at test time.
Experimental results show that our method significantly improves LLMs
performance and reveals two meaningful insights: 1) Code structural knowledge
can be effectively post-incorporated into pre-trained LLMs during inference,
despite being overlooked during training; 2) Scaling up model size or training
data does not lead to the emergence of code structural knowledge, underscoring
the necessity of explicitly considering code syntactic structure.
