---
layout: publication
title: 'Prophet: Prompting Large Language Models With Complementary Answer Heuristics For Knowledge-based Visual Question Answering'
authors: Zhou Yu, Xuecheng Ouyang, Zhenwei Shao, Meng Wang, Jun Yu
conference: "Arxiv"
year: 2023
bibkey: yu2023prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.01903"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Multimodal Models', 'Prompting']
---
Knowledge-based visual question answering (VQA) requires external knowledge
beyond the image to answer the question. Early studies retrieve required
knowledge from explicit knowledge bases (KBs), which often introduces
irrelevant information to the question, hence restricting the performance of
their models. Recent works have resorted to using a powerful large language
model (LLM) as an implicit knowledge engine to acquire the necessary knowledge
for answering. Despite the encouraging results achieved by these methods, we
argue that they have not fully activated the capacity of the *blind* LLM
as the provided textual input is insufficient to depict the required visual
information to answer the question. In this paper, we present Prophet -- a
conceptually simple, flexible, and general framework designed to prompt LLM
with answer heuristics for knowledge-based VQA. Specifically, we first train a
vanilla VQA model on a specific knowledge-based VQA dataset without external
knowledge. After that, we extract two types of complementary answer heuristics
from the VQA model: answer candidates and answer-aware examples. The two types
of answer heuristics are jointly encoded into a formatted prompt to facilitate
the LLM's understanding of both the image and question, thus generating a more
accurate answer. By incorporating the state-of-the-art LLM GPT-3, Prophet
significantly outperforms existing state-of-the-art methods on four challenging
knowledge-based VQA datasets. Prophet is general that can be instantiated with
the combinations of different VQA models (i.e., both discriminative and
generative ones) and different LLMs (i.e., both commercial and open-source
ones). Moreover, Prophet can also be integrated with modern large multimodal
models in different stages, which is named Prophet++, to further improve the
capabilities on knowledge-based VQA tasks.
