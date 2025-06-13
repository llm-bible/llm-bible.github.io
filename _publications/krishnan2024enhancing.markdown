---
layout: publication
title: 'Enhancing Trust In Large Language Models With Uncertainty-aware Fine-tuning'
authors: Ranganath Krishnan, Piyush Khanna, Omesh Tickoo
conference: "Arxiv"
year: 2024
bibkey: krishnan2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.02904"}
tags: ['Fine-Tuning', 'Language Modeling', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) have revolutionized the field of natural
language processing with their impressive reasoning and question-answering
capabilities. However, these models are sometimes prone to generating
credible-sounding but incorrect information, a phenomenon known as LLM
hallucinations. Reliable uncertainty estimation in LLMs is essential for
fostering trust in their generated responses and serves as a critical tool for
the detection and prevention of erroneous or hallucinated outputs. To achieve
reliable and well-calibrated uncertainty quantification in open-ended and
free-form natural language generation, we propose an uncertainty-aware
fine-tuning approach for LLMs. This approach enhances the model's ability to
provide reliable uncertainty estimates without compromising accuracy, thereby
guiding them to produce more trustworthy responses. We introduce a novel
uncertainty-aware causal language modeling loss function, grounded in the
principles of decision theory. Through rigorous evaluation on multiple
free-form question-answering datasets and models, we demonstrate that our
uncertainty-aware fine-tuning approach yields better calibrated uncertainty
estimates in natural language generation tasks than fine-tuning with the
standard causal language modeling loss. Furthermore, the experimental results
show that the proposed method significantly improves the model's ability to
detect hallucinations and identify out-of-domain prompts.
