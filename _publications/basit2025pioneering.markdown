---
layout: publication
title: 'Pennylang: Pioneering Llm-based Quantum Code Generation With A Novel Pennylane-centric Dataset'
authors: Abdul Basit, Nouhaila Innan, Haider Asif, Minghao Shao, Muhammad Kashif, Alberto Marchisio, Muhammad Shafique
conference: "Arxiv"
year: 2025
bibkey: basit2025pioneering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.02497'}
tags: ['RAG', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Prompting', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) offer remarkable capabilities in code
generation, natural language processing, and domain-specific reasoning.
However, their application in quantum software development remains
underexplored, particularly for PennyLane-a leading framework for hybrid
quantum-classical computing. To address this gap, we introduce a novel,
high-quality dataset comprising 3,347 PennyLane-specific quantum code samples
and contextual descriptions, specifically curated to support LLM training and
fine-tuning for quantum code assistance. Our contributions are threefold: (1)
the automatic construction and open-source release of a comprehensive PennyLane
dataset derived from textbooks, official documentation, and open-source
repositories; (2) a structured methodology for data curation, annotation, and
formatting to enhance LLM usability and relevance; and (3) a rigorous
evaluation of code generation capabilities using both baseline
Retrieval-Augmented Generation (RAG) and a GraphRAG-enhanced pipeline. Using
the PennyLang framework, we demonstrate that GraphRAG, when applied to a GPT-4o
Mini model, substantially outperforms standard prompting and baseline RAG.
Accuracy improves from 20.5% (without RAG) to 58.2% with GraphRAG, showcasing
its effectiveness in reducing hallucinations and improving code correctness in
quantum programming tasks. Compared to prior efforts focused largely on Qiskit,
our work expands LLM-based assistance to the PennyLane ecosystem, contributing
practical tools and reproducible methodologies for advancing AI-assisted
quantum software development.
