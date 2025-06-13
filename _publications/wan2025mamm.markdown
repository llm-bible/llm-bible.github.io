---
layout: publication
title: 'Mamm-refine: A Recipe For Improving Faithfulness In Generation With Multi-agent Collaboration'
authors: David Wan, Justin Chih-yao Chen, Elias Stengel-eskin, Mohit Bansal
conference: "Arxiv"
year: 2025
bibkey: wan2025mamm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.15272'}
tags: ['Agentic', 'Applications']
---
Multi-agent collaboration among models has shown promise in reasoning tasks
but is underexplored in long-form generation tasks like summarization and
question-answering. We extend multi-agent multi-model reasoning to generation,
specifically to improving faithfulness through refinement, i.e., revising
model-generated outputs to remove factual inconsistencies. We investigate how
iterative collaboration among multiple instances and types of large language
models (LLMs) enhances subtasks in the refinement process, such as error
detection, critiquing unfaithful sentences, and making corrections based on
critiques. We design intrinsic evaluations for each subtask, with our findings
indicating that both multi-agent (multiple instances) and multi-model (diverse
LLM types) approaches benefit error detection and critiquing. Additionally,
reframing critiquing and refinement as reranking rather than generation tasks
improves multi-agent performance. We consolidate these insights into a final
"recipe" called Multi-Agent Multi-Model Refinement (MAMM-Refine), where
multi-agent and multi-model collaboration significantly boosts performance on
three summarization datasets as well as on long-form question answering,
demonstrating the effectiveness and generalizability of our recipe.
