---
layout: publication
title: EPA Easy Prompt Augmentation On Large Language Models Via Multiple Sources And Multiple Targets
authors: Lu Hongyuan, Lam Wai
conference: "Arxiv"
year: 2023
bibkey: lu2023easy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04725"}
tags: ['Applications', 'Prompting']
---
Large language models (LLMs) have shown promising performance on various NLP tasks via task prompting. And their performance can be further improved by appending task demonstrations to the head of the prompt. And usually a better performance can be achieved with more demonstrations. However asking the users to write the demonstrations can be cumbersome. As a simple yet cost45;effective workaround this paper proposes a novel method called EPA (textbf123;E125;asy textbf123;P125;rompt textbf123;A125;ugmentation)footnote123;While this paper considers augmenting prompts via demonstrations we name it EPA as the name EDA is already taken by a well45;known NLP method citep123;wei45;zou45;201945;eda125;.125; that effectively minimizes user efforts in writing demonstrations while improving the model performance at the same time. EPA achieves these goals by automatically augmenting the demonstrations with multiple sources/targets where each of them paraphrases each other. This is well motivated as augmenting data via paraphrasing effectively improves neural language models. EPA thus employs paraphrasing as an augmentation method for in45;context learning. Extensive experiments indicate that EPA effectively improves both NLU and NLG tasks covering from natural language inference to machine translation in translating tens of languages.footnote123;Code and data will be released upon publication.125;
