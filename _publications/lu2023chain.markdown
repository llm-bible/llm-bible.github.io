---
layout: publication
title: Chain45;of45;dictionary Prompting Elicits Translation In Large Language Models
authors: Lu Hongyuan, Yang Haoran, Huang Haoyang, Zhang Dongdong, Lam Wai, Wei Furu
conference: "Arxiv"
year: 2023
bibkey: lu2023chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.06575"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have shown surprisingly good performance in multilingual neural machine translation (MNMT) even when trained without parallel data. Yet despite the fact that the amount of training data is gigantic they still struggle with translating rare words particularly for low45;resource languages. Even worse it is usually unrealistic to retrieve relevant demonstrations for in45;context learning with low45;resource languages on LLMs which restricts the practical use of LLMs for translation 45;45; how should we mitigate this problem To this end we present a novel method CoD which augments LLMs with prior knowledge with the chains of multilingual dictionaries for a subset of input words to elicit translation abilities for LLMs. Extensive experiments indicate that augmenting ChatGPT with CoD elicits large gains by up to 13x chrF++ points for MNMT (3.08 to 42.63 for English to Serbian written in Cyrillic script) on FLORES45;200 full devtest set. We further demonstrate the importance of chaining the multilingual dictionaries as well as the superiority of CoD to few45;shot demonstration for low45;resource languages.
