---
layout: publication
title: From Artificial Needles To Real Haystacks&#58; Improving Retrieval Capabilities In Llms By Finetuning On Synthetic Data
authors: Xiong Zheyang, Papageorgiou Vasilis, Lee Kangwook, Papailiopoulos Dimitris
conference: "Arxiv"
year: 2024
bibkey: xiong2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19292"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG']
---
Recent studies have shown that Large Language Models (LLMs) struggle to accurately retrieve information and maintain reasoning capabilities when processing long-context inputs. To address these limitations we propose a finetuning approach utilizing a carefully designed synthetic dataset comprising numerical key-value retrieval tasks. Our experiments on models like GPT-3.5 Turbo and Mistral 7B demonstrate that finetuning LLMs on this dataset significantly improves LLMs information retrieval and reasoning capabilities in longer-context settings. We present an analysis of the finetuned models illustrating the transfer of skills from synthetic to real task evaluations (e.g. 10.537; improvement on 20 documents MDQA at position 10 for GPT-3.5 Turbo). We also find that finetuned LLMs performance on general benchmarks remains almost constant while LLMs finetuned on other baseline long-context augmentation data can encourage hallucination (e.g. on TriviaQA Mistral 7B finetuned on our synthetic data cause no performance drop while other baseline data can cause a drop that ranges from 2.3337; to 6.1937;). Our study highlights the potential of finetuning on synthetic data for improving the performance of LLMs on longer-context tasks.
