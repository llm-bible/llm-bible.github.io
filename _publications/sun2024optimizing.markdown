---
layout: publication
title: 'Optimizing Social Media Annotation Of HPV Vaccine Skepticism And Misinformation Using Large Language Models: An Experimental Evaluation Of In-context Learning And Fine-tuning Stance Detection Across Multiple Models'
authors: Luhang Sun, Varsha Pendyala, Yun-shiuan Chuang, Shanglin Yang, Jonathan Feldman, Andrew Zhao, Munmun De Choudhury, Sijia Yang, Dhavan Shah
conference: "Arxiv"
year: 2024
bibkey: sun2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.14720"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
This paper leverages large-language models (LLMs) to experimentally determine
optimal strategies for scaling up social media content annotation for stance
detection on HPV vaccine-related tweets. We examine both conventional
fine-tuning and emergent in-context learning methods, systematically varying
strategies of prompt engineering across widely used LLMs and their variants
(e.g., GPT4, Mistral, and Llama3, etc.). Specifically, we varied prompt
template design, shot sampling methods, and shot quantity to detect stance on
HPV vaccination. Our findings reveal that 1) in general, in-context learning
outperforms fine-tuning in stance detection for HPV vaccine social media
content; 2) increasing shot quantity does not necessarily enhance performance
across models; and 3) different LLMs and their variants present differing
sensitivity to in-context learning conditions. We uncovered that the optimal
in-context learning configuration for stance detection on HPV vaccine tweets
involves six stratified shots paired with detailed contextual prompts. This
study highlights the potential and provides an applicable approach for applying
LLMs to research on social media stance and skepticism detection.
