---
layout: publication
title: 'Seek And Solve Reasoning For Table Question Answering'
authors: Ruya Jiang, Chun Wang, Weihong Deng
conference: "Arxiv"
year: 2024
bibkey: jiang2024seek
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.05286'}
tags: ['RAG', 'Prompting', 'Applications']
---
The complexities of table structures and question logic make table-based
question answering (TQA) tasks challenging for Large Language Models (LLMs),
often requiring task simplification before solving. This paper reveals that the
reasoning process during task simplification may be more valuable than the
simplified tasks themselves and aims to improve TQA performance by leveraging
LLMs' reasoning capabilities. We propose a Seek-and-Solve pipeline that
instructs the LLM to first seek relevant information and then answer questions,
integrating these two stages at the reasoning level into a coherent
Seek-and-Solve Chain of Thought (SS-CoT). Additionally, we distill a
single-step TQA-solving prompt from this pipeline, using demonstrations with
SS-CoT paths to guide the LLM in solving complex TQA tasks under In-Context
Learning settings. Our experiments show that our approaches result in improved
performance and reliability while being efficient. Our findings emphasize the
importance of eliciting LLMs' reasoning capabilities to handle complex TQA
tasks effectively.
