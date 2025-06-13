---
layout: publication
title: 'Code-mixer Ya Nahi: Novel Approaches To Measuring Multilingual Llms'' Code-mixing Capabilities'
authors: Ayushman Gupta, Akhil Bhogal, Kripabandhu Ghosh
conference: "Arxiv"
year: 2024
bibkey: gupta2024code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11079"}
tags: ['Model Architecture', 'Reinforcement Learning', 'GPT', 'Prompting', 'Applications']
---
Multilingual Large Language Models (LLMs) have demonstrated exceptional
performance in Machine Translation (MT) tasks. However, their MT abilities in
the context of code-switching (the practice of mixing two or more languages in
an utterance) remain under-explored. In this paper, we introduce Rule-Based
Prompting, a novel prompting technique to generate code-mixed sentences. We
measure and compare the code-mixed MT abilities of 3 popular multilingual LLMs:
GPT-3.5-turbo, GPT-4, and Gemini Pro across five language pairs:
English-\{Hindi, Bengali, Gujarati, French, Spanish\} using \\(k\\)-shot prompting
(\\(k\in\\{0, 1, 10, 20\\}\\)) and Rule-Based Prompting. Our findings suggest that
though \\(k\\)-shot prompting often leads to the best results, Rule-Based prompting
shows promise in generating unique code-mixed sentences that vary in their
style of code-mixing. We also use \\(k\\)-shot prompting to gauge the code-mixed to
English translation abilities of multilingual LLMs. For this purpose, we create
a gold-standard code-mixed dataset spanning five language pairs:
English-\{Hindi, Bengali, Gujarati, French, Spanish\}. As a real-world
application of our work, we create a code-mixed chatbot.
