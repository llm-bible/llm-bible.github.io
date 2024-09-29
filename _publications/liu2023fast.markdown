---
layout: publication
title: 'BOLT: Fast Energy-based Controlled Text Generation With Tunable Biases'
authors: Liu Xin, Khalifa Muhammad, Wang Lu
conference: "Arxiv"
year: 2023
bibkey: liu2023fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12018"}
tags: ['Applications', 'Efficiency And Optimization', 'Ethics And Bias', 'GPT', 'Language Modeling', 'Pretraining Methods', 'Reinforcement Learning']
---
Energy-based models (EBMs) have gained popularity for controlled text generation due to their high applicability to a wide range of constraints. However sampling from EBMs is non-trivial as it often requires a large number of iterations to converge to plausible text which slows down the decoding process and makes it less practical for real-world applications. In this work we propose BOLT which relies on tunable biases to directly adjust the language models output logits. Unlike prior work BOLT maintains the generators autoregressive nature to assert a strong control on token-wise conditional dependencies and overall fluency and thus converges faster. When compared with state-of-the-arts on controlled generation tasks using both soft constraints (e.g. sentiment control) and hard constraints (e.g. keyword-guided topic control) BOLT demonstrates significantly improved efficiency and fluency. On sentiment control BOLT is 7x faster than competitive baselines and more fluent in 74.437; of the evaluation samples according to human judges.
