---
layout: publication
title: 'Dr. Jekyll And Mr. Hyde: Two Faces Of Llms'
authors: Matteo Gioele Collu, Tom Janssen-groesbeek, Stefanos Koffas, Mauro Conti, Stjepan Picek
conference: "Arxiv"
year: 2023
bibkey: collu2023jekyll
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.03853'}
tags: ['Security', 'GPT', 'Applications', 'Model Architecture', 'Responsible AI']
---
Recently, we have witnessed a rise in the use of Large Language Models
(LLMs), especially in applications like chatbots. Safety mechanisms are
implemented to prevent improper responses from these chatbots. In this work, we
bypass these measures for ChatGPT and Gemini by making them impersonate complex
personas with personality characteristics that are not aligned with a truthful
assistant. First, we create elaborate biographies of these personas, which we
then use in a new session with the same chatbots. Our conversations then follow
a role-play style to elicit prohibited responses. Using personas, we show that
prohibited responses are provided, making it possible to obtain unauthorized,
illegal, or harmful information in both ChatGPT and Gemini. We also introduce
several ways of activating such adversarial personas, showing that both
chatbots are vulnerable to this attack. With the same principle, we introduce
two defenses that push the model to interpret trustworthy personalities and
make it more robust against such attacks.
