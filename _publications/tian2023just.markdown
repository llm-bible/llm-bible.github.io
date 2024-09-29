---
layout: publication
title: Just Ask For Calibration Strategies For Eliciting Calibrated Confidence Scores From Language Models Fine45;tuned With Human Feedback
authors: Tian Katherine, Mitchell Eric, Zhou Allan, Sharma Archit, Rafailov Rafael, Yao Huaxiu, Finn Chelsea, Manning Christopher D.
conference: "Arxiv"
year: 2023
bibkey: tian2023just
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14975"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
A trustworthy real45;world prediction system should produce well45;calibrated confidence scores; that is its confidence in an answer should be indicative of the likelihood that the answer is correct enabling deferral to an expert in cases of low45;confidence predictions. Recent studies have shown that unsupervised pre45;training produces large language models (LMs) whose conditional probabilities are remarkably well45;calibrated. However the most widely45;used LMs are fine45;tuned with reinforcement learning from human feedback (RLHF45;LMs) and some studies have suggested that RLHF45;LMs produce conditional probabilities that are very poorly calibrated. In light of this perceived weakness we conduct a broad evaluation of methods for extracting confidence scores from RLHF45;LMs. For RLHF45;LMs such as ChatGPT GPT45;4 and Claude we find that verbalized confidences emitted as output tokens are typically better45;calibrated than the models conditional probabilities on the TriviaQA SciQ and TruthfulQA benchmarks often reducing the expected calibration error by a relative 5037;.
