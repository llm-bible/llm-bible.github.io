---
layout: publication
title: '\(\texttt{sage}\): A Generic Framework For LLM Safety Evaluation'
authors: Madhur Jindal, Hari Shrawgi, Parag Agrawal, Sandipan Dandapat
conference: "Arxiv"
year: 2025
bibkey: jindal2025generic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.19674"}
tags: ['Responsible AI', 'Security', 'Tools', 'Reinforcement Learning', 'Applications']
---
Safety evaluation of Large Language Models (LLMs) has made progress and
attracted academic interest, but it remains challenging to keep pace with the
rapid integration of LLMs across diverse applications. Different applications
expose users to various harms, necessitating application-specific safety
evaluations with tailored harms and policies. Another major gap is the lack of
focus on the dynamic and conversational nature of LLM systems. Such potential
oversights can lead to harms that go unnoticed in standard safety benchmarks.
This paper identifies the above as key requirements for robust LLM safety
evaluation and recognizing that current evaluation methodologies do not satisfy
these, we introduce the \\(\texttt\{SAGE\}\\) (Safety AI Generic Evaluation)
framework. \\(\texttt\{SAGE\}\\) is an automated modular framework designed for
customized and dynamic harm evaluations. It utilizes adversarial user models
that are system-aware and have unique personalities, enabling a holistic
red-teaming evaluation. We demonstrate \\(\texttt\{SAGE\}\\)'s effectiveness by
evaluating seven state-of-the-art LLMs across three applications and harm
policies. Our experiments with multi-turn conversational evaluations revealed a
concerning finding that harm steadily increases with conversation length.
Furthermore, we observe significant disparities in model behavior when exposed
to different user personalities and scenarios. Our findings also reveal that
some models minimize harmful outputs by employing severe refusal tactics that
can hinder their usefulness. These insights highlight the necessity of adaptive
and context-specific testing to ensure better safety alignment and safer
deployment of LLMs in real-world scenarios.
