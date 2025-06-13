---
layout: publication
title: 'Re-ranking The Context For Multimodal Retrieval Augmented Generation'
authors: Matin Mortaheb, Mohammad A. Amir Khojastepour, Srimat T. Chakradhar, Sennur Ulukus
conference: "Arxiv"
year: 2025
bibkey: mortaheb2025re
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.04695"}
tags: ['Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT']
---
Retrieval-augmented generation (RAG) enhances large language models (LLMs) by
incorporating external knowledge to generate a response within a context with
improved accuracy and reduced hallucinations. However, multi-modal RAG systems
face unique challenges: (i) the retrieval process may select irrelevant entries
to user query (e.g., images, documents), and (ii) vision-language models or
multi-modal language models like GPT-4o may hallucinate when processing these
entries to generate RAG output. In this paper, we aim to address the first
challenge, i.e, improving the selection of relevant context from the
knowledge-base in retrieval phase of the multi-modal RAG. Specifically, we
leverage the relevancy score (RS) measure designed in our previous work for
evaluating the RAG performance to select more relevant entries in retrieval
process. The retrieval based on embeddings, say CLIP-based embedding, and
cosine similarity usually perform poorly particularly for multi-modal data. We
show that by using a more advanced relevancy measure, one can enhance the
retrieval process by selecting more relevant pieces from the knowledge-base and
eliminate the irrelevant pieces from the context by adaptively selecting
up-to-\\(k\\) entries instead of fixed number of entries. Our evaluation using COCO
dataset demonstrates significant enhancement in selecting relevant context and
accuracy of the generated response.
