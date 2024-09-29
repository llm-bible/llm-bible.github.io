---
layout: publication
title: Language Models Do Hard Arithmetic Tasks Easily And Hardly Do Easy Arithmetic Tasks
authors: Gambardella Andrew, Iwasawa Yusuke, Matsuo Yutaka
conference: "Arxiv"
year: 2024
bibkey: gambardella2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02356"}
tags: ['Pretraining Methods', 'RAG']
---
The ability (and inability) of large language models (LLMs) to perform arithmetic tasks has been the subject of much theoretical and practical debate. We show that LLMs are frequently able to correctly and confidently predict the first digit of n45;digit by m45;digit multiplication tasks without using chain of thought reasoning despite these tasks require compounding operations to solve. Simultaneously LLMs in practice often fail to correctly or confidently predict the last digit of an n45;digit by m45;digit multiplication a task equivalent to 145;digit by 145;digit multiplication which can be easily learned or memorized. We show that the latter task can be solved more robustly when the LLM is conditioned on all of the correct higher45;order digits which on average increases the confidence of the correct last digit on 545;digit by 545;digit multiplication tasks using Llama 245;13B by over 23037; (0.13 to 0.43) and Mistral45;7B by 15037; (0.22 to 0.55).
