---
layout: publication
title: 'Towards Robust Evaluation Of Unlearning In Llms Via Data Transformations'
authors: Abhinav Joshi, Shaswati Saha, Divyaksh Shukla, Sriram Vema, Harsh Jhamtani, Manas Gaur, Ashutosh Modi
conference: "Arxiv"
year: 2024
bibkey: joshi2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15477"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Applications']
---
Large Language Models (LLMs) have shown to be a great success in a wide range
of applications ranging from regular NLP-based use cases to AI agents. LLMs
have been trained on a vast corpus of texts from various sources; despite the
best efforts during the data pre-processing stage while training the LLMs, they
may pick some undesirable information such as personally identifiable
information (PII). Consequently, in recent times research in the area of
Machine Unlearning (MUL) has become active, the main idea is to force LLMs to
forget (unlearn) certain information (e.g., PII) without suffering from
performance loss on regular tasks. In this work, we examine the robustness of
the existing MUL techniques for their ability to enable leakage-proof
forgetting in LLMs. In particular, we examine the effect of data transformation
on forgetting, i.e., is an unlearned LLM able to recall forgotten information
if there is a change in the format of the input? Our findings on the TOFU
dataset highlight the necessity of using diverse data formats to quantify
unlearning in LLMs more reliably.
