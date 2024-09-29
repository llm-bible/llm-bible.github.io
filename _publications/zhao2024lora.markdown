---
layout: publication
title: Lora Land 310 Fine45;tuned Llms That Rival GPT45;4 A Technical Report
authors: Zhao Justin, Wang Timothy, Abid Wael, Angus Geoffrey, Garg Arnav, Kinnison Jeffery, Sherstinsky Alex, Molino Piero, Addair Travis, Rishi Devvret
conference: "Arxiv"
year: 2024
bibkey: zhao2024lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00732"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Low Rank Adaptation (LoRA) has emerged as one of the most widely adopted methods for Parameter Efficient Fine45;Tuning (PEFT) of Large Language Models (LLMs). LoRA reduces the number of trainable parameters and memory usage while achieving comparable performance to full fine45;tuning. We aim to assess the viability of training and serving LLMs fine45;tuned with LoRA in real45;world applications. First we measure the quality of LLMs fine45;tuned with quantized low rank adapters across 10 base models and 31 tasks for a total of 310 models. We find that 445;bit LoRA fine45;tuned models outperform base models by 34 points and GPT45;4 by 10 points on average. Second we investigate the most effective base models for fine45;tuning and assess the correlative and predictive capacities of task complexity heuristics in forecasting the outcomes of fine45;tuning. Finally we evaluate the latency and concurrency capabilities of LoRAX an open45;source Multi45;LoRA inference server that facilitates the deployment of multiple LoRA fine45;tuned models on a single GPU using shared base model weights and dynamic adapter loading. LoRAX powers LoRA Land a web application that hosts 25 LoRA fine45;tuned Mistral45;7B LLMs on a single NVIDIA A100 GPU with 80GB memory. LoRA Land highlights the quality and cost45;effectiveness of employing multiple specialized LLMs over a single general45;purpose LLM.
