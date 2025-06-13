---
layout: publication
title: 'GEM-RAG: Graphical Eigen Memories For Retrieval Augmented Generation'
authors: Brendan Hogan Rappazzo, Yingheng Wang, Aaron Ferber, Carla Gomes
conference: "Arxiv"
year: 2024
bibkey: rappazzo2024gem
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.15566"}
tags: ['Agentic', 'GPT', 'Tools', 'Applications', 'RAG', 'Model Architecture', 'BERT', 'Prompting']
---
The ability to form, retrieve, and reason about memories in response to
stimuli serves as the cornerstone for general intelligence - shaping entities
capable of learning, adaptation, and intuitive insight. Large Language Models
(LLMs) have proven their ability, given the proper memories or context, to
reason and respond meaningfully to stimuli. However, they are still unable to
optimally encode, store, and retrieve memories - the ability to do this would
unlock their full ability to operate as AI agents, and to specialize to niche
domains. To remedy this, one promising area of research is Retrieval Augmented
Generation (RAG), which aims to augment LLMs by providing them with rich
in-context examples and information. In question-answering (QA) applications,
RAG methods embed the text of interest in chunks, and retrieve the most
relevant chunks for a prompt using text embeddings. Motivated by human memory
encoding and retrieval, we aim to improve over standard RAG methods by
generating and encoding higher-level information and tagging the chunks by
their utility to answer questions. We introduce Graphical Eigen Memories For
Retrieval Augmented Generation (GEM-RAG). GEM-RAG works by tagging each chunk
of text in a given text corpus with LLM generated ``utility'' questions,
connecting chunks in a graph based on the similarity of both their text and
utility questions, and then using the eigendecomposition of the memory graph to
build higher level summary nodes that capture the main themes of the text. We
evaluate GEM-RAG, using both UnifiedQA and GPT-3.5 Turbo as the LLMs, with
SBERT, and OpenAI's text encoders on two standard QA tasks, showing that
GEM-RAG outperforms other state-of-the-art RAG methods on these tasks. We also
discuss the implications of having a robust RAG system and future directions.
