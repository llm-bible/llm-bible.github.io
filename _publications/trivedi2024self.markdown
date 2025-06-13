---
layout: publication
title: 'Self-rationalization Improves LLM As A Fine-grained Judge'
authors: Prapti Trivedi, Aditya Gulati, Oliver Molenschot, Meghana Arakkal Rajeev, Rajkumar Ramamurthy, Keith Stevens, Tanveesh Singh Chaudhery, Jahnavi Jambholkar, James Zou, Nazneen Rajani
conference: "Arxiv"
year: 2024
bibkey: trivedi2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05495"}
tags: ['Fine-Tuning', 'Ethics and Bias', 'RAG', 'Reinforcement Learning', 'Interpretability', 'Training Techniques', 'Pretraining Methods']
---
LLM-as-a-judge models have been used for evaluating both human and AI
generated content, specifically by providing scores and rationales. Rationales,
in addition to increasing transparency, help models learn to calibrate its
judgments. Enhancing a model's rationale can therefore improve its calibration
abilities and ultimately the ability to score content. We introduce
Self-Rationalization, an iterative process of improving the rationales for the
judge models, which consequently improves the score for fine-grained
customizable scoring criteria (i.e., likert-scale scoring with arbitrary
evaluation criteria). Self-rationalization works by having the model generate
multiple judgments with rationales for the same input, curating a preference
pair dataset from its own judgements, and iteratively fine-tuning the judge via
DPO. Intuitively, this approach allows the judge model to self-improve by
learning from its own rationales, leading to better alignment and evaluation
accuracy. After just two iterations -- while only relying on examples in the
training set -- human evaluation shows that our judge model learns to produce
higher quality rationales, with a win rate of \\(62%\\) on average compared to
models just trained via SFT on rationale . This judge model also achieves high
scoring accuracy on BigGen Bench and Reward Bench, outperforming even bigger
sized models trained using SFT with rationale, self-consistency or best-of-\\(N\\)
sampling by \\(3%\\) to \\(9%\\).
