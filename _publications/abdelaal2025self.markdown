---
layout: publication
title: 'GLLM: Self-corrective G-code Generation Using Large Language Models With User Feedback'
authors: Mohamed Abdelaal, Samuel Lokadjaja, Gilbert Engert
conference: "Industrial Track of 21st Conference on Database Systems for Business Technology and Web (BTW) 2025"
year: 2025
bibkey: abdelaal2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.17584"}
tags: ['Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Prompting']
---
This paper introduces GLLM, an innovative tool that leverages Large Language
Models (LLMs) to automatically generate G-code from natural language
instructions for Computer Numerical Control (CNC) machining. GLLM addresses the
challenges of manual G-code writing by bridging the gap between human-readable
task descriptions and machine-executable code. The system incorporates a
fine-tuned StarCoder-3B model, enhanced with domain-specific training data and
a Retrieval-Augmented Generation (RAG) mechanism. GLLM employs advanced
prompting strategies and a novel self-corrective code generation approach to
ensure both syntactic and semantic correctness of the generated G-code. The
architecture includes robust validation mechanisms, including syntax checks,
G-code-specific verifications, and functional correctness evaluations using
Hausdorff distance. By combining these techniques, GLLM aims to democratize CNC
programming, making it more accessible to users without extensive programming
experience while maintaining high accuracy and reliability in G-code
generation.
