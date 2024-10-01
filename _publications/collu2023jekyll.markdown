---
layout: publication
title: 'Dr. Jekyll And Mr. Hyde: Two Faces Of Llms'
authors: Collu Matteo Gioele, Janssen-groesbeek Tom, Koffas Stefanos, Conti Mauro, Picek Stjepan
conference: "Arxiv"
year: 2023
bibkey: collu2023jekyll
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.03853"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Responsible AI', 'Security', 'Training Techniques']
---
Recently, we have witnessed a rise in the use of Large Language Models (LLMs), especially in applications like chatbot assistants. Safety mechanisms and specialized training procedures are implemented to prevent improper responses from these assistants. In this work, we bypass these measures for ChatGPT and Gemini (and, to some extent, Bing chat) by making them impersonate complex personas with personality characteristics that are not aligned with a truthful assistant. We start by creating elaborate biographies of these personas, which we then use in a new session with the same chatbots. Our conversations then follow a role-play style to elicit prohibited responses. Using personas, we show that prohibited responses are actually provided, making it possible to obtain unauthorized, illegal, or harmful information. This work shows that by using adversarial personas, one can overcome safety mechanisms set out by ChatGPT and Gemini. We also introduce several ways of activating such adversarial personas, which show that both chatbots are vulnerable to this kind of attack. With the same principle, we introduce two defenses that push the model to interpret trustworthy personalities and make it more robust against such attacks.
