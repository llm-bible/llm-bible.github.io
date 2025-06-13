---
layout: publication
title: 'Multilingual Prompting For Improving LLM Generation Diversity'
authors: Qihan Wang, Shidong Pan, Tal Linzen, Emily Black
conference: "Arxiv"
year: 2025
bibkey: wang2025multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15229"}
tags: ['Prompting', 'Training Techniques', 'GPT', 'Model Architecture']
---
Large Language Models (LLMs) are known to lack cultural representation and overall diversity in their generations, from expressing opinions to answering factual questions. To mitigate this problem, we propose multilingual prompting: a prompting method which generates several variations of a base prompt with added cultural and linguistic cues from several cultures, generates responses, and then combines the results. Building on evidence that LLMs have language-specific knowledge, multilingual prompting seeks to increase diversity by activating a broader range of cultural knowledge embedded in model training data. Through experiments across multiple models (GPT-4o, GPT-4o-mini, LLaMA 70B, and LLaMA 8B), we show that multilingual prompting consistently outperforms existing diversity-enhancing techniques such as high-temperature sampling, step-by-step recall, and personas prompting. Further analyses show that the benefits of multilingual prompting vary with language resource level and model size, and that aligning the prompting language with the cultural cues reduces hallucination about culturally-specific information.
