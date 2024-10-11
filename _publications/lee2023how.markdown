---
layout: publication
title: 'How Well Do Large Language Models Truly Ground?'
authors: Lee Hyunji, Joo Sejune, Kim Chaeeun, Jang Joel, Kim Doyoung, On Kyoung-woon, Seo Minjoon
conference: "Arxiv"
year: 2023
bibkey: lee2023how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09069"}
tags: ['Applications', 'Training Techniques', 'Uncategorized']
---
To reduce issues like hallucinations and lack of control in Large Language Models (LLMs), a common method is to generate responses by grounding on external contexts given as input, known as knowledge-augmented models. However, previous research often narrowly defines grounding as just having the correct answer, which does not ensure the reliability of the entire response. To overcome this, we propose a stricter definition of grounding: a model is truly grounded if it (1) fully utilizes the necessary knowledge from the provided context, and (2) stays within the limits of that knowledge. We introduce a new dataset and a grounding metric to evaluate model capability under the definition. We perform experiments across 25 LLMs of different sizes and training methods and provide insights into factors that influence grounding performance. Our findings contribute to a better understanding of how to improve grounding capabilities and suggest an area of improvement toward more reliable and controllable LLM applications.
