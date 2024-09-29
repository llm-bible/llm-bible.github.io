---
layout: publication
title: Complexity45;based Prompting For Multi45;step Reasoning
authors: Fu Yao, Peng Hao, Sabharwal Ashish, Clark Peter, Khot Tushar
conference: "Arxiv"
year: 2022
bibkey: fu2022complexity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.00720"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Security']
---
We study the task of prompting large45;scale language models to perform multi45;step reasoning. Existing work shows that when prompted with a chain of thoughts (CoT) sequences of short sentences describing intermediate reasoning steps towards a final answer large language models can generate new reasoning chains and predict answers for new inputs. A central question is which reasoning examples make the most effective prompts. In this work we propose complexity45;based prompting a simple and effective example selection scheme for multi45;step reasoning. We show that prompts with higher reasoning complexity i.e. chains with more reasoning steps achieve substantially better performance on multi45;step reasoning tasks over strong baselines. We further extend our complexity45;based criteria from prompting (selecting inputs) to decoding (selecting outputs) where we sample multiple reasoning chains from the model then choose the majority of generated answers from complex reasoning chains (over simple chains). When used to prompt GPT45;3 and Codex our approach substantially improves multi45;step reasoning accuracy and achieves new state45;of45;the45;art (SOTA) performance on three math benchmarks (GSM8K MultiArith and MathQA) and two BigBenchHard tasks (Date Understanding and Penguins) with an average +5.3 and up to +18 accuracy improvements. Compared with existing example selection schemes like manual tuning or retrieval45;based selection selection based on reasoning complexity is intuitive easy to implement and annotation45;efficient. Further results demonstrate the robustness of performance gains from complex prompts under format perturbation and distribution shift.
