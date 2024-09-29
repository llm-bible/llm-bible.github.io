---
layout: publication
title: Efficient Finetuning Large Language Models For Vietnamese Chatbot
authors: Doan Vu-thuan, Truong Quoc-truong, Nguyen Duc-vu, Nguyen Vinh-tiep, Luu Thuy-ngan Nguyen
conference: "Arxiv"
year: 2023
bibkey: doan2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04646"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large language models (LLMs) such as GPT45;4 PaLM and LLaMa have been shown to achieve remarkable performance across a variety of natural language tasks. Recent advancements in instruction tuning bring LLMs with ability in following users instructions and producing human45;like responses. However the high costs associated with training and implementing LLMs pose challenges to academic research. Furthermore the availability of pretrained LLMs and instruction45;tune datasets for Vietnamese language is limited. To tackle these concerns we leverage large45;scale instruction45;following datasets from open45;source projects namely Alpaca GPT4All and Chat45;Doctor which cover general domain and specific medical domain. To the best of our knowledge these are the first instructional dataset for Vietnamese. Subsequently we utilize parameter45;efficient tuning through Low45;Rank Adaptation (LoRA) on two open LLMs Bloomz (Multilingual) and GPTJ45;6B (Vietnamese) resulting four models Bloomz45;Chat Bloomz45;Doctor GPTJ45;Chat GPTJ45;Doctor.Finally we assess the effectiveness of our methodology on a per45;sample basis taking into consideration the helpfulness relevance accuracy level of detail in their responses. This evaluation process entails the utilization of GPT45;4 as an automated scoring mechanism. Despite utilizing a low45;cost setup our method demonstrates about 2045;3037; improvement over the original models in our evaluation tasks.
