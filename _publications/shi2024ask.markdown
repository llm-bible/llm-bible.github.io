---
layout: publication
title: 'Ask-eda: A Design Assistant Empowered By LLM, Hybrid RAG And Abbreviation De-hallucination'
authors: Shi Luyao, Kazda Michael, Sears Bradley, Shropshire Nick, Puri Ruchir
conference: "Arxiv"
year: 2024
bibkey: shi2024ask
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06575"}
tags: ['Agentic', 'Applications', 'RAG']
---
Electronic design engineers are challenged to find relevant information
efficiently for a myriad of tasks within design construction, verification and
technology development. Large language models (LLM) have the potential to help
improve productivity by serving as conversational agents that effectively
function as subject-matter experts. In this paper we demonstrate Ask-EDA, a
chat agent designed to serve as a 24x7 expert available to provide guidance to
design engineers. Ask-EDA leverages LLM, hybrid retrieval augmented generation
(RAG) and abbreviation de-hallucination (ADH) techniques to deliver more
relevant and accurate responses. We curated three evaluation datasets, namely
q2a-100, cmds-100 and abbr-100. Each dataset is tailored to assess a distinct
aspect: general design question answering, design command handling and
abbreviation resolution. We demonstrated that hybrid RAG offers over a 40%
improvement in Recall on the q2a-100 dataset and over a 60% improvement on the
cmds-100 dataset compared to not using RAG, while ADH yields over a 70%
enhancement in Recall on the abbr-100 dataset. The evaluation results show that
Ask-EDA can effectively respond to design-related inquiries.
