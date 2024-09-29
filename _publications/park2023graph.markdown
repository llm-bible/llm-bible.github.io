---
layout: publication
title: Graph Elicitation For Guiding Multi45;step Reasoning In Large Language Models
authors: Park Jinyoung, Patel Ameen, Khan Omar Zia, Kim Hyunwoo J., Kim Joo-kyung
conference: "Arxiv"
year: 2023
bibkey: park2023graph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09762"}
tags: ['Applications', 'Prompting', 'RAG']
---
Chain45;of45;Thought (CoT) prompting along with sub45;question generation and answering has enhanced multi45;step reasoning capabilities of Large Language Models (LLMs). However prompting the LLMs to directly generate sub45;questions is suboptimal since they sometimes generate redundant or irrelevant questions. To deal with them we propose a GE45;Reasoning method which directs LLMs to generate proper sub45;questions and corresponding answers. Concretely given an input question we first prompt the LLM to generate knowledge triplets forming a graph representation of the question. Unlike conventional knowledge triplets our approach allows variables as head or tail entities effectively representing a question as knowledge triplets. Second for each triplet the LLM generates a corresponding sub45;question and answer along with using knowledge retrieval. If the prediction confidence exceeds a threshold the sub45;question and prediction are incorporated into the prompt for subsequent processing. This approach encourages that sub45;questions are grounded in the extracted knowledge triplets reducing redundancy and irrelevance. Our experiments demonstrate that our approach outperforms previous CoT prompting methods and their variants on multi45;hop question answering benchmark datasets.
