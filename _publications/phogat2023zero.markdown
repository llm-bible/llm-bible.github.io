---
layout: publication
title: 'Zero-shot Question Answering Over Financial Documents Using Large Language Models'
authors: Karmvir Singh Phogat, Chetan Harsha, Sridhar Dasaratha, Shashishekar Ramakrishna, Sai Akhil Puranam
conference: "Arxiv"
year: 2023
bibkey: phogat2023zero
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.14722'}
tags: ['Transformer', 'Few-Shot', 'GPT', 'Applications', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
We introduce a large language model (LLM) based approach to answer complex
questions requiring multi-hop numerical reasoning over financial reports. While
LLMs have exhibited remarkable performance on various natural language and
reasoning tasks, complex reasoning problems often rely on few-shot prompts that
require carefully crafted examples. In contrast, our approach uses novel
zero-shot prompts that guide the LLM to encode the required reasoning into a
Python program or a domain specific language. The generated program is then
executed by a program interpreter, thus mitigating the limitations of LLM in
performing accurate arithmetic calculations.
  We evaluate the proposed approach on three financial datasets using some of
the recently developed generative pretrained transformer (GPT) models and
perform comparisons with various zero-shot baselines. The experimental results
demonstrate that our approach significantly improves the accuracy for all the
LLMs over their respective baselines. We provide a detailed analysis of the
results, generating insights to support our findings. The success of our
approach demonstrates the enormous potential to extract complex domain specific
numerical reasoning by designing zero-shot prompts to effectively exploit the
knowledge embedded in LLMs.
