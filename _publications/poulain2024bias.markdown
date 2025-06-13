---
layout: publication
title: 'Bias Patterns In The Application Of Llms For Clinical Decision Support: A Comprehensive Study'
authors: Raphael Poulain, Hamed Fayyaz, Rahmatollah Beheshti
conference: "Arxiv"
year: 2024
bibkey: poulain2024bias
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.15149"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Prompting', 'Applications']
---
Large Language Models (LLMs) have emerged as powerful candidates to inform
clinical decision-making processes. While these models play an increasingly
prominent role in shaping the digital landscape, two growing concerns emerge in
healthcare applications: 1) to what extent do LLMs exhibit social bias based on
patients' protected attributes (like race), and 2) how do design choices (like
architecture design and prompting strategies) influence the observed biases? To
answer these questions rigorously, we evaluated eight popular LLMs across three
question-answering (QA) datasets using clinical vignettes (patient
descriptions) standardized for bias evaluations. We employ red-teaming
strategies to analyze how demographics affect LLM outputs, comparing both
general-purpose and clinically-trained models. Our extensive experiments reveal
various disparities (some significant) across protected groups. We also observe
several counter-intuitive patterns such as larger models not being necessarily
less biased and fined-tuned models on medical data not being necessarily better
than the general-purpose models. Furthermore, our study demonstrates the impact
of prompt design on bias patterns and shows that specific phrasing can
influence bias patterns and reflection-type approaches (like Chain of Thought)
can reduce biased outcomes effectively. Consistent with prior studies, we call
on additional evaluations, scrutiny, and enhancement of LLMs used in clinical
decision support applications.
