---
layout: publication
title: 'HALO: Hallucination Analysis And Learning Optimization To Empower Llms With Retrieval-augmented Context For Guided Clinical Decision Making'
authors: Sumera Anjum, Hanzhi Zhang, Wenjun Zhou, Eun Jin Paek, Xiaopeng Zhao, Yunhe Feng
conference: "Arxiv"
year: 2024
bibkey: anjum2024hallucination
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.10011"}
  - {name: "Code", url: "https://github.com/ResponsibleAILab/HALO"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Interpretability', 'Has Code']
---
Large language models (LLMs) have significantly advanced natural language
processing tasks, yet they are susceptible to generating inaccurate or
unreliable responses, a phenomenon known as hallucination. In critical domains
such as health and medicine, these hallucinations can pose serious risks. This
paper introduces HALO, a novel framework designed to enhance the accuracy and
reliability of medical question-answering (QA) systems by focusing on the
detection and mitigation of hallucinations. Our approach generates multiple
variations of a given query using LLMs and retrieves relevant information from
external open knowledge bases to enrich the context. We utilize maximum
marginal relevance scoring to prioritize the retrieved context, which is then
provided to LLMs for answer generation, thereby reducing the risk of
hallucinations. The integration of LangChain further streamlines this process,
resulting in a notable and robust increase in the accuracy of both open-source
and commercial LLMs, such as Llama-3.1 (from 44% to 65%) and ChatGPT (from 56%
to 70%). This framework underscores the critical importance of addressing
hallucinations in medical QA systems, ultimately improving clinical
decision-making and patient care. The open-source HALO is available at:
https://github.com/ResponsibleAILab/HALO.
