---
layout: publication
title: 'Superpipeline: A Universal Approach For Reducing GPU Memory Usage In Large Models'
authors: Reza Abbasi, Sernam Lim
conference: "Arxiv"
year: 2024
bibkey: abbasi2024universal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.08791'}
  - {name: "Code", url: 'https://github.com/abbasiReza/super-pipeline'}
tags: ['Has Code', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Multimodal Models', 'Pretraining Methods']
---
The rapid growth in machine learning models, especially in natural language
processing and computer vision, has led to challenges when running these models
on hardware with limited resources. This paper introduces Superpipeline, a new
framework designed to optimize the execution of large AI models on constrained
hardware during both training and inference. Our approach involves dynamically
managing model execution by dividing models into individual layers and
efficiently transferring these layers between GPU and CPU memory. Superpipeline
reduces GPU memory usage by up to 60% in our experiments while maintaining
model accuracy and acceptable processing speeds. This allows models that would
otherwise exceed available GPU memory to run effectively. Unlike existing
solutions that focus mainly on inference or specific model types, Superpipeline
can be applied to large language models (LLMs), vision-language models (VLMs),
and vision-based models. We tested Superpipeline's performance across various
models and hardware setups. The method includes two key parameters that allow
fine-tuning the balance between GPU memory use and processing speed.
Importantly, Superpipeline does not require retraining or changing model
parameters, ensuring that the original model's output remains unchanged.
Superpipeline's simplicity and flexibility make it useful for researchers and
professionals working with advanced AI models on limited hardware. It enables
the use of larger models or bigger batch sizes on existing hardware,
potentially speeding up innovation across many machine learning applications.
This work marks an important step toward making advanced AI models more
accessible and optimizing their deployment in resource-limited environments.
The code for Superpipeline is available at
https://github.com/abbasiReza/super-pipeline.
