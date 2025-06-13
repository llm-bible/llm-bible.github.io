---
layout: publication
title: 'Teleoracle: Fine-tuned Retrieval-augmented Generation With Long-context Support For Network'
authors: Nouf Alabbasi, Omar Erak, Omar Alhussein, Ismail Lotfi, Sami Muhaidat, Merouane Debbah
conference: "Arxiv"
year: 2024
bibkey: alabbasi2024fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.02617'}
tags: ['ACL', 'RAG', 'Training Techniques', 'Tools', 'Merging', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
The telecommunications industry's rapid evolution demands intelligent systems
capable of managing complex networks and adapting to emerging technologies.
While large language models (LLMs) show promise in addressing these challenges,
their deployment in telecom environments faces significant constraints due to
edge device limitations and inconsistent documentation. To bridge this gap, we
present TeleOracle, a telecom-specialized retrieval-augmented generation (RAG)
system built on the Phi-2 small language model (SLM). To improve context
retrieval, TeleOracle employs a two-stage retriever that incorporates semantic
chunking and hybrid keyword and semantic search. Additionally, we expand the
context window during inference to enhance the model's performance on
open-ended queries. We also employ low-rank adaption for efficient fine-tuning.
A thorough analysis of the model's performance indicates that our RAG framework
is effective in aligning Phi-2 to the telecom domain in a downstream question
and answer (QnA) task, achieving a 30% improvement in accuracy over the base
Phi-2 model, reaching an overall accuracy of 81.20%. Notably, we show that our
model not only performs on par with the much larger LLMs but also achieves a
higher faithfulness score, indicating higher adherence to the retrieved
context.
