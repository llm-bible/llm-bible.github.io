---
layout: publication
title: 'Fine-tuning Language Models For Ethical Ambiguity: A Comparative Study Of Alignment With Human Responses'
authors: Pranav Senthilkumar, Visshwa Balasubramanian, Prisha Jain, Aneesa Maity, Jonathan Lu, Kevin Zhu
conference: "Arxiv"
year: 2024
bibkey: senthilkumar2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.07826"}
tags: ['Fine-Tuning', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
Language models often misinterpret human intentions due to their handling of
ambiguity, a limitation well-recognized in NLP research. While morally clear
scenarios are more discernible to LLMs, greater difficulty is encountered in
morally ambiguous contexts. In this investigation, we explored LLM calibration
to show that human and LLM judgments are poorly aligned in such scenarios. We
used two curated datasets from the Scruples project for evaluation: DILEMMAS,
which involves pairs of distinct moral scenarios to assess the model's ability
to compare and contrast ethical situations, and ANECDOTES, which presents
individual narratives to evaluate the model's skill in drawing out details,
interpreting, and analyzing distinct moral scenarios. Model answer
probabilities were extracted for all possible choices and compared with human
annotations to benchmark the alignment of three models: Llama-3.1-8b,
Zephyr-7b-beta, and Mistral-7b. Significant improvements were observed after
fine-tuning, with notable enhancements in both cross-entropy and Dirichlet
scores, particularly in the latter. Notably, after fine-tuning, the performance
of Mistral-7B-Instruct-v0.3 was on par with GPT-4o. However, the experimental
models that were examined were all still outperformed by the BERT and RoBERTa
models in terms of cross-entropy scores. Our fine-tuning approach, which
improves the model's understanding of text distributions in a text-to-text
format, effectively enhances performance and alignment in complex
decision-making contexts, underscoring the need for further research to refine
ethical reasoning techniques and capture human judgment nuances.
