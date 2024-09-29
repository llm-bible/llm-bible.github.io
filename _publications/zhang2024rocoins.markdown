---
layout: publication
title: RoCoIns Enhancing Robustness of Large Language Models through Code-Style Instructions
authors: Zhang Yuansen, Wang Xiao, Xi Zhiheng, Xia Han, Gui Tao, Zhang Qi, Huang Xuanjing
conference: "Arxiv"
year: 2024
bibkey: zhang2024rocoins
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16431"}
tags: ['Few Shot', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security']
---
Large Language Models (LLMs) have showcased remarkable capabilities in following human instructions. However recent studies have raised concerns about the robustness of LLMs when prompted with instructions combining textual adversarial samples. In this paper drawing inspiration from recent works that LLMs are sensitive to the design of the instructions we utilize instructions in code style which are more structural and less ambiguous to replace typically natural language instructions. Through this conversion we provide LLMs with more precise instructions and strengthen the robustness of LLMs. Moreover under few-shot scenarios we propose a novel method to compose in-context demonstrations using both clean and adversarial samples () to further boost the robustness of the LLMs. Experiments on eight robustness datasets show that our method consistently outperforms prompting LLMs with natural language instructions. For example with gpt-3.5-turbo our method achieves an improvement of 5.68 in test set accuracy and a reduction of 5.66 points in Attack Success Rate (ASR).
