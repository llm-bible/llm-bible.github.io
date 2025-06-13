---
layout: publication
title: 'Graph-augmented Reasoning: Evolving Step-by-step Knowledge Graph Retrieval For LLM Reasoning'
authors: Wenjie Wu, Yongcheng Jing, Yingjie Wang, Wenbin Hu, Dacheng Tao
conference: "Arxiv"
year: 2025
bibkey: wu2025graph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01642"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Applications']
---
Recent large language model (LLM) reasoning, despite its success, suffers
from limited domain knowledge, susceptibility to hallucinations, and
constrained reasoning depth, particularly in small-scale models deployed in
resource-constrained environments. This paper presents the first investigation
into integrating step-wise knowledge graph retrieval with step-wise reasoning
to address these challenges, introducing a novel paradigm termed as
graph-augmented reasoning. Our goal is to enable frozen, small-scale LLMs to
retrieve and process relevant mathematical knowledge in a step-wise manner,
enhancing their problem-solving abilities without additional training. To this
end, we propose KG-RAR, a framework centered on process-oriented knowledge
graph construction, a hierarchical retrieval strategy, and a universal
post-retrieval processing and reward model (PRP-RM) that refines retrieved
information and evaluates each reasoning step. Experiments on the Math500 and
GSM8K benchmarks across six models demonstrate that KG-RAR yields encouraging
results, achieving a 20.73% relative improvement with Llama-3B on Math500.
