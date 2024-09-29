---
layout: publication
title: Bounding The Capabilities Of Large Language Models In Open Text Generation With Prompt Constraints
authors: Lu Albert, Zhang Hongxin, Zhang Yanzhe, Wang Xuezhi, Yang Diyi
conference: "Arxiv"
year: 2023
bibkey: lu2023bounding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.09185"}
  - {name: "Code", url: "https://github.com/SALT-NLP/Bound-Cap-LLM"}
tags: ['Applications', 'GPT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Prompting']
---
The limits of open-ended generative models are unclear yet increasingly important. What causes them to succeed and what causes them to fail In this paper we take a prompt-centric approach to analyzing and bounding the abilities of open-ended generative models. We present a generic methodology of analysis with two challenging prompt constraint types structural and stylistic. These constraint types are categorized into a set of well-defined constraints that are analyzable by a single prompt. We then systematically create a diverse set of simple natural and useful prompts to robustly analyze each individual constraint. Using the GPT-3 text-davinci-002 model as a case study we generate outputs from our collection of prompts and analyze the models generative failures. We also show the generalizability of our proposed method on other large models like BLOOM and OPT. Our results and our in-context mitigation strategies reveal open challenges for future research. We have publicly released our code at https://github.com/SALT-NLP/Bound-Cap-LLM."
