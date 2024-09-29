---
layout: publication
title: In-context Time Series Predictor
authors: Lu Jiecheng, Sun Yan, Yang Shihao
conference: "Arxiv"
year: 2024
bibkey: lu2024time
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14982"}
tags: ['Few Shot', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
Recent Transformer-based large language models (LLMs) demonstrate in-context learning ability to perform various functions based solely on the provided context without updating model parameters. To fully utilize the in-context capabilities in time series forecasting (TSF) problems unlike previous Transformer-based or LLM-based time series forecasting methods we reformulate time series forecasting tasks as input tokens by constructing a series of (lookback future) pairs within the tokens. This method aligns more closely with the inherent in-context mechanisms and is more parameter-efficient without the need of using pre-trained LLM parameters. Furthermore it addresses issues such as overfitting in existing Transformer-based TSF models consistently achieving better performance across full-data few-shot and zero-shot settings compared to previous architectures.
