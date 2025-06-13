---
layout: publication
title: 'Advancing Conversational Diagnostic AI With Multimodal Reasoning'
authors: Khaled Saab, Jan Freyberg, Chunjong Park, Tim Strother, Yong Cheng, Wei-hung Weng, David G. T. Barrett, David Stutz, Nenad Tomasev, Anil Palepu, Valentin Liévin, Yash Sharma, Roma Ruparel, Abdullah Ahmed, Elahe Vedadi, Kimberly Kanada, Cian Hughes, Yun Liu, Geoff Brown, Yang Gao, Sean Li, S. Sara Mahdavi, James Manyika, Katherine Chou, Yossi Matias, Avinatan Hassidim, Dale R. Webster, Pushmeet Kohli, S. M. Ali Eslami, Joëlle Barral, Adam Rodman, Vivek Natarajan, Mike Schaekermann, Tao Tu, Alan Karthikesalingam, Ryutaro Tanno
conference: "Arxiv"
year: 2025
bibkey: saab2025advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04653"}
tags: ['RAG', 'Multimodal Models', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated great potential for conducting
diagnostic conversations but evaluation has been largely limited to
language-only interactions, deviating from the real-world requirements of
remote care delivery. Instant messaging platforms permit clinicians and
patients to upload and discuss multimodal medical artifacts seamlessly in
medical consultation, but the ability of LLMs to reason over such data while
preserving other attributes of competent diagnostic conversation remains
unknown. Here we advance the conversational diagnosis and management
performance of the Articulate Medical Intelligence Explorer (AMIE) through a
new capability to gather and interpret multimodal data, and reason about this
precisely during consultations. Leveraging Gemini 2.0 Flash, our system
implements a state-aware dialogue framework, where conversation flow is
dynamically controlled by intermediate model outputs reflecting patient states
and evolving diagnoses. Follow-up questions are strategically directed by
uncertainty in such patient states, leading to a more structured multimodal
history-taking process that emulates experienced clinicians. We compared AMIE
to primary care physicians (PCPs) in a randomized, blinded, OSCE-style study of
chat-based consultations with patient actors. We constructed 105 evaluation
scenarios using artifacts like smartphone skin photos, ECGs, and PDFs of
clinical documents across diverse conditions and demographics. Our rubric
assessed multimodal capabilities and other clinically meaningful axes like
history-taking, diagnostic accuracy, management reasoning, communication, and
empathy. Specialist evaluation showed AMIE to be superior to PCPs on 7/9
multimodal and 29/32 non-multimodal axes (including diagnostic accuracy). The
results show clear progress in multimodal conversational diagnostic AI, but
real-world translation needs further research.
