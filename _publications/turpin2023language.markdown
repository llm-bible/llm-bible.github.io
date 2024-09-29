---
layout: publication
title: Language Models Dont Always Say What They Think Unfaithful Explanations In Chain-of-thought Prompting
authors: Turpin Miles, Michael Julian, Perez Ethan, Bowman Samuel R.
conference: "Arxiv"
year: 2023
bibkey: turpin2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.04388"}
tags: ['Ethics And Bias', 'Few Shot', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Responsible AI']
---
Large Language Models (LLMs) can achieve strong performance on many tasks by producing step-by-step reasoning before giving a final output often referred to as chain-of-thought reasoning (CoT). It is tempting to interpret these CoT explanations as the LLMs process for solving a task. This level of transparency into LLMs predictions would yield significant safety benefits. However we find that CoT explanations can systematically misrepresent the true reason for a models prediction. We demonstrate that CoT explanations can be heavily influenced by adding biasing features to model inputs--e.g. by reordering the multiple-choice options in a few-shot prompt to make the answer always (A)--which models systematically fail to mention in their explanations. When we bias models toward incorrect answers they frequently generate CoT explanations rationalizing those answers. This causes accuracy to drop by as much as 3637; on a suite of 13 tasks from BIG-Bench Hard when testing with GPT-3.5 from OpenAI and Claude 1.0 from Anthropic. On a social-bias task model explanations justify giving answers in line with stereotypes without mentioning the influence of these social biases. Our findings indicate that CoT explanations can be plausible yet misleading which risks increasing our trust in LLMs without guaranteeing their safety. Building more transparent and explainable systems will require either improving CoT faithfulness through targeted efforts or abandoning CoT in favor of alternative methods.
