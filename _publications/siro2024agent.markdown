---
layout: publication
title: 'AGENT-CQ: Automatic Generation And Evaluation Of Clarifying Questions For Conversational Search With Llms'
authors: Clemencia Siro, Yifei Yuan, Mohammad Aliannejadi, Maarten De Rijke
conference: "Arxiv"
year: 2024
bibkey: siro2024agent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.19692"}
tags: ['Prompting', 'Agentic', 'Tools']
---
Generating diverse and effective clarifying questions is crucial for
improving query understanding and retrieval performance in open-domain
conversational search (CS) systems. We propose AGENT-CQ (Automatic GENeration,
and evaluaTion of Clarifying Questions), an end-to-end LLM-based framework
addressing the challenges of scalability and adaptability faced by existing
methods that rely on manual curation or template-based approaches. AGENT-CQ
consists of two stages: a generation stage employing LLM prompting strategies
to generate clarifying questions, and an evaluation stage (CrowdLLM) that
simulates human crowdsourcing judgments using multiple LLM instances to assess
generated questions and answers based on comprehensive quality metrics.
Extensive experiments on the ClariQ dataset demonstrate CrowdLLM's
effectiveness in evaluating question and answer quality. Human evaluation and
CrowdLLM show that the AGENT-CQ - generation stage, consistently outperforms
baselines in various aspects of question and answer quality. In retrieval-based
evaluation, LLM-generated questions significantly enhance retrieval
effectiveness for both BM25 and cross-encoder models compared to
human-generated questions.
