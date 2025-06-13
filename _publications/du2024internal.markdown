---
layout: publication
title: 'Internal And External Knowledge Interactive Refinement Framework For Knowledge-intensive Question Answering'
authors: Haowei Du, Dongyan Zhao
conference: "Arxiv"
year: 2024
bibkey: du2024internal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12979"}
tags: ['Prompting', 'Applications', 'Survey Paper', 'Tools']
---
Recent works have attempted to integrate external knowledge into LLMs to
address the limitations and potential factual errors in LLM-generated content.
However, how to retrieve the correct knowledge from the large amount of
external knowledge imposes a challenge. To this end, we empirically observe
that LLMs have already encoded rich knowledge in their pretrained parameters
and utilizing these internal knowledge improves the retrieval of external
knowledge when applying them to knowledge-intensive tasks. In this paper, we
propose a new internal and external knowledge interactive refinement paradigm
dubbed IEKR to utilize internal knowledge in LLM to help retrieve relevant
knowledge from the external knowledge base, as well as exploit the external
knowledge to refine the hallucination of generated internal knowledge. By
simply adding a prompt like 'Tell me something about' to the LLMs, we try to
review related explicit knowledge and insert them with the query into the
retriever for external retrieval. The external knowledge is utilized to
complement the internal knowledge into input of LLM for answers. We conduct
experiments on 3 benchmark datasets in knowledge-intensive question answering
task with different LLMs and domains, achieving the new state-of-the-art.
Further analysis shows the effectiveness of different modules in our approach.
