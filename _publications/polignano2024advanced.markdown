---
layout: publication
title: Advanced Natural45;based Interaction For The Italian Language Llamantino45;345;anita
authors: Polignano Marco, Basile Pierpaolo, Semeraro Giovanni
conference: "Arxiv"
year: 2024
bibkey: polignano2024advanced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07101"}
  - {name: "Code", url: "https://huggingface.co/swap&#45;uniba/LLaMAntino&#45;3&#45;ANITA&#45;8B&#45;Inst&#45;DPO&#45;ITA"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'Fine Tuning', 'Has Code', 'RAG', 'Reinforcement Learning']
---
In the pursuit of advancing natural language processing for the Italian language we introduce a state45;of45;the45;art Large Language Model (LLM) based on the novel Meta LLaMA45;3 model LLaMAntino45;345;ANITA45;8B45;Inst45;DPO45;ITA. We fine45;tuned the original 8B parameters instruction tuned model using the Supervised Fine45;tuning (SFT) technique on the English and Italian language datasets in order to improve the original performance. Consequently a Dynamic Preference Optimization (DPO) process has been used to align preferences avoid dangerous and inappropriate answers and limit biases and prejudices. Our model leverages the efficiency of QLoRA to fine45;tune the model on a smaller portion of the original model weights and then adapt the model specifically for the Italian linguistic structure achieving significant improvements in both performance and computational efficiency. Concurrently DPO is employed to refine the models output ensuring that generated content aligns with quality answers. The synergy between SFT QLoRAs parameter efficiency and DPOs user45;centric optimization results in a robust LLM that excels in a variety of tasks including but not limited to text completion zero45;shot classification and contextual understanding. The model has been extensively evaluated over standard benchmarks for the Italian and English languages showing outstanding results. The model is freely available over the HuggingFace hub and examples of use can be found in our GitHub repository. https://huggingface.co/swap&#45;uniba/LLaMAntino&#45;3&#45;ANITA&#45;8B&#45;Inst&#45;DPO&#45;ITA
