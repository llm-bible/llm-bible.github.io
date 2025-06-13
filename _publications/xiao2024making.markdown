---
layout: publication
title: 'Molly: Making Large Language Model Agents Solve Python Problem More Logically'
authors: Rui Xiao, Jiong Wang, Lu Han, Na Zong, Han Wu
conference: "Arxiv"
year: 2024
bibkey: xiao2024making
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.18093'}
tags: ['Attention Mechanism', 'Agentic', 'RAG', 'Training Techniques', 'Model Architecture', 'Merging', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Applying large language models (LLMs) as teaching assists has attracted much
attention as an integral part of intelligent education, particularly in
computing courses. To reduce the gap between the LLMs and the computer
programming education expert, fine-tuning and retrieval augmented generation
(RAG) are the two mainstream methods in existing researches. However,
fine-tuning for specific tasks is resource-intensive and may diminish the
model`s generalization capabilities. RAG can perform well on reducing the
illusion of LLMs, but the generation of irrelevant factual content during
reasoning can cause significant confusion for learners. To address these
problems, we introduce the Molly agent, focusing on solving the proposed
problem encountered by learners when learning Python programming language. Our
agent automatically parse the learners' questioning intent through a
scenario-based interaction, enabling precise retrieval of relevant documents
from the constructed knowledge base. At generation stage, the agent reflect on
the generated responses to ensure that they not only align with factual content
but also effectively answer the user's queries. Extensive experimentation on a
constructed Chinese Python QA dataset shows the effectiveness of the Molly
agent, indicating an enhancement in its performance for providing useful
responses to Python questions.
