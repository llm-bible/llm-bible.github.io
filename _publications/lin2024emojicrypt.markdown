---
layout: publication
title: EmojiCrypt Prompt Encryption for Secure Communication with Large Language Models
authors: Lin Guo, Hua Wenyue, Zhang Yongfeng
conference: "Arxiv"
year: 2024
bibkey: lin2024emojicrypt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05868"}
  - {name: "Code", url: "https://github.com/agiresearch/EmojiCrypt"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Security', 'Tools']
---
Cloud-based large language models (LLMs) such as ChatGPT have increasingly become integral to daily operations serving as vital tools across various applications. While these models offer substantial benefits in terms of accessibility and functionality they also introduce significant privacy concerns the transmission and storage of user data in cloud infrastructures pose substantial risks of data breaches and unauthorized access to sensitive information; even if the transmission and storage of data is encrypted the LLM service provider itself still knows the real contents of the data preventing individuals or entities from confidently using such LLM services. To address these concerns this paper proposes a simple yet effective mechanism EmojiCrypt to protect user privacy. It uses Emoji to encrypt the user inputs before sending them to LLM effectively rendering them indecipherable to human or LLMs examination while retaining the original intent of the prompt thus ensuring the models performance remains unaffected. We conduct experiments on three tasks personalized recommendation sentiment analysis and tabular data analysis. Experiment results reveal that EmojiCrypt can encrypt personal information within prompts in such a manner that not only prevents the discernment of sensitive data by humans or LLM itself but also maintains or even improves the precision without further tuning achieving comparable or even better task accuracy than directly prompting the LLM without prompt encryption. These results highlight the practicality of adopting encryption measures that safeguard user privacy without compromising the functional integrity and performance of LLMs. Code and dataset are available at https://github.com/agiresearch/EmojiCrypt.
