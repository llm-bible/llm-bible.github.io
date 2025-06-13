---
layout: publication
title: 'Calibrated Decision-making Through Llm-assisted Retrieval'
authors: Chaeyun Jang, Hyungi Lee, Seanie Lee, Juho Lee
conference: "Arxiv"
year: 2024
bibkey: jang2024calibrated
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.08891'}
tags: ['Reinforcement Learning', 'RAG']
---
Recently, large language models (LLMs) have been increasingly used to support
various decision-making tasks, assisting humans in making informed decisions.
However, when LLMs confidently provide incorrect information, it can lead
humans to make suboptimal decisions. To prevent LLMs from generating incorrect
information on topics they are unsure of and to improve the accuracy of
generated content, prior works have proposed Retrieval Augmented Generation
(RAG), where external documents are referenced to generate responses. However,
traditional RAG methods focus only on retrieving documents most relevant to the
input query, without specifically aiming to ensure that the human user's
decisions are well-calibrated. To address this limitation, we propose a novel
retrieval method called Calibrated Retrieval-Augmented Generation (CalibRAG),
which ensures that decisions informed by the retrieved documents are
well-calibrated. Then we empirically validate that CalibRAG improves
calibration performance as well as accuracy, compared to other baselines across
various datasets.
