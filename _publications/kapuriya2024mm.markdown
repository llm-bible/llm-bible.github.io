---
layout: publication
title: 'Mm-phyrlhf: Reinforcement Learning Framework For Multimodal Physics Question-answering'
authors: Janak Kapuriya, Chhavi Kirtani, Apoorv Singh, Jay Saraf, Naman Lal, Jatin Kumar, Adarsh Raj Shivam, Astha Verma, Avinash Anand, Rajiv Ratn Shah
conference: "Arxiv"
year: 2024
bibkey: kapuriya2024mm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.12926"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'Applications', 'Interpretability and Explainability', 'Reinforcement Learning', 'Multimodal Models']
---
Recent advancements in LLMs have shown their significant potential in tasks
like text summarization and generation. Yet, they often encounter difficulty
while solving complex physics problems that require arithmetic calculation and
a good understanding of concepts. Moreover, many physics problems include
images that contain important details required to understand the problem's
context. We propose an LMM-based chatbot to answer multimodal physics MCQs. For
domain adaptation, we utilize the MM-PhyQA dataset comprising Indian high
school-level multimodal physics problems. To improve the LMM's performance, we
experiment with two techniques, RLHF (Reinforcement Learning from Human
Feedback) and Image Captioning. In image captioning, we add a detailed
explanation of the diagram in each image, minimizing hallucinations and image
processing errors. We further explore the integration of Reinforcement Learning
from Human Feedback (RLHF) methodology inspired by the ranking approach in RLHF
to enhance the human-like problem-solving abilities of the models. The RLHF
approach incorporates human feedback into the learning process of LLMs,
improving the model's problem-solving skills, truthfulness, and reasoning
capabilities, minimizing the hallucinations in the answers, and improving the
quality instead of using vanilla-supervised fine-tuned models. We employ the
LLaVA open-source model to answer multimodal physics MCQs and compare the
performance with and without using RLHF.
