---
layout: publication
title: 'Autodrive-qa- Automated Generation Of Multiple-choice Questions For Autonomous Driving Datasets Using Large Vision-language Models'
authors: Boshra Khalili, Andrew W. Smyth
conference: "Arxiv"
year: 2025
bibkey: khalili2025autodrive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.15778"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Ethics and Bias', 'Applications']
---
In autonomous driving, open-ended question answering often suffers from
unreliable evaluations because freeform responses require either complex
metrics or subjective human judgment. To address this challenge, we introduce
AutoDrive-QA, an automatic pipeline that converts existing driving QA datasets
(including DriveLM, NuScenes-QA, and LingoQA) into a structured multiple-choice
question (MCQ) format. This benchmark systematically assesses perception,
prediction, and planning tasks, providing a standardized and objective
evaluation framework. AutoDrive-QA employs an automated pipeline that leverages
large language models (LLMs) to generate high-quality, contextually relevant
distractors based on domain-specific error patterns commonly found in
autonomous driving scenarios. To evaluate both general capabilities and
generalization performance, we test the benchmark on three public datasets and
conduct zero-shot experiments on an unseen dataset. The zero-shot evaluations
reveal that GPT-4V leads with 69.57% accuracy -- achieving 74.94% in
Perception, 65.33% in Prediction, and 68.45% in Planning -- demonstrating that
while all models excel in Perception, they struggle in Prediction.
Consequently, AutoDrive-QA establishes a rigorous, unbiased standard for
integrating and evaluating different vision-language models across various
autonomous driving datasets, thereby improving generalization in this field. We
release all the codes in the AutoDrive-QA GitHub Repository.
