---
layout: publication
title: 'EPA: Easy Prompt Augmentation On Large Language Models Via Multiple Sources And Multiple Targets'
authors: Lu Hongyuan, Lam Wai
conference: "Arxiv"
year: 2023
bibkey: lu2023easy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04725"}
tags: ['Applications', 'In Context Learning', 'Prompting']
---
Large language models (LLMs) have shown promising performance on various NLP tasks via task prompting. And their performance can be further improved by appending task demonstrations to the head of the prompt. And usually a better performance can be achieved with more demonstrations. However asking the users to write the demonstrations can be cumbersome. As a simple yet cost-effective workaround this paper proposes a novel method called EPA (textbfEasy textbfPrompt textbfAugmentation)footnoteWhile this paper considers augmenting prompts via demonstrations we name it EPA as the name EDA is already taken by a well-known NLP method citepwei-zou-2019-eda. that effectively minimizes user efforts in writing demonstrations while improving the model performance at the same time. EPA achieves these goals by automatically augmenting the demonstrations with multiple sources/targets where each of them paraphrases each other. This is well motivated as augmenting data via paraphrasing effectively improves neural language models. EPA thus employs paraphrasing as an augmentation method for in-context learning. Extensive experiments indicate that EPA effectively improves both NLU and NLG tasks covering from natural language inference to machine translation in translating tens of languages.footnoteCode and data will be released upon publication.
