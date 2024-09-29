---
layout: publication
title: 'Learning From Red Teaming: Gender Bias Provocation And Mitigation In Large Language Models'
authors: Su Hsuan, Cheng Cheng-chu, Farn Hua, Kumar Shachi H, Sahay Saurav, Chen Shang-tse, Lee Hung-yi
conference: "Arxiv"
year: 2023
bibkey: su2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.11079"}
tags: ['Applications', 'Ethics And Bias', 'Fine Tuning', 'GPT', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Recently researchers have made considerable improvements in dialogue systems with the progress of large language models (LLMs) such as ChatGPT and GPT-4. These LLM-based chatbots encode the potential biases while retaining disparities that can harm humans during interactions. The traditional biases investigation methods often rely on human-written test cases. However these test cases are usually expensive and limited. In this work we propose a first-of-its-kind method that automatically generates test cases to detect LLMs potential gender bias. We apply our method to three well-known LLMs and find that the generated test cases effectively identify the presence of biases. To address the biases identified we propose a mitigation strategy that uses the generated test cases as demonstrations for in-context learning to circumvent the need for parameter fine-tuning. The experimental results show that LLMs generate fairer responses with the proposed approach.
