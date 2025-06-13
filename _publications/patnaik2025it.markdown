---
layout: publication
title: 'It Helps To Take A Second Opinion: Teaching Smaller Llms To Deliberate Mutually Via Selective Rationale Optimisation'
authors: Sohan Patnaik, Milan Aggarwal, Sumit Bhatia, Balaji Krishnamurthy
conference: "Arxiv"
year: 2025
bibkey: patnaik2025it
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02463"}
  - {name: "Code", url: "https://github.com/Sohanpatnaik106/coalition"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Distillation', 'GPT', 'Has Code']
---
Very large language models (LLMs) such as GPT-4 have shown the ability to
handle complex tasks by generating and self-refining step-by-step rationales.
Smaller language models (SLMs), typically with < 13B parameters, have been
improved by using the data generated from very-large LMs through knowledge
distillation. However, various practical constraints such as API costs,
copyright, legal and ethical policies restrict using large (often opaque)
models to train smaller models for commercial use. Limited success has been
achieved at improving the ability of an SLM to explore the space of possible
rationales and evaluate them by itself through self-deliberation. To address
this, we propose COALITION, a trainable framework that facilitates interaction
between two variants of the same SLM and trains them to generate and refine
rationales optimized for the end-task. The variants exhibit different behaviors
to produce a set of diverse candidate rationales during the generation and
refinement steps. The model is then trained via Selective Rationale
Optimization (SRO) to prefer generating rationale candidates that maximize the
likelihood of producing the ground-truth answer. During inference, COALITION
employs a controller to select the suitable variant for generating and refining
the rationales. On five different datasets covering mathematical problems,
commonsense reasoning, and natural language inference, COALITION outperforms
several baselines by up to 5%. Our ablation studies reveal that
cross-communication between the two variants performs better than using the
single model to self-refine the rationales. We also demonstrate the
applicability of COALITION for LMs of varying scales (4B to 14B parameters) and
model families (Mistral, Llama, Qwen, Phi). We release the code for this work
at https://github.com/Sohanpatnaik106/coalition.
