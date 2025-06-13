---
layout: publication
title: 'Prompt Inject Detection With Generative Explanation As An Investigative Tool'
authors: Jonathan Pan, Swee Liang Wong, Yidi Yuan, Xin Wei Chia
conference: "Arxiv"
year: 2025
bibkey: pan2025prompt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11006'}
tags: ['Language Modeling', 'Interpretability and Explainability', 'Security', 'Applications', 'Fine-Tuning', 'Prompting']
---
Large Language Models (LLMs) are vulnerable to adversarial prompt based
injects. These injects could jailbreak or exploit vulnerabilities within these
models with explicit prompt requests leading to undesired responses. In the
context of investigating prompt injects, the challenge is the sheer volume of
input prompts involved that are likely to be largely benign. This investigative
challenge is further complicated by the semantics and subjectivity of the input
prompts involved in the LLM conversation with its user and the context of the
environment to which the conversation is being carried out. Hence, the
challenge for AI security investigators would be two-fold. The first is to
identify adversarial prompt injects and then to assess whether the input prompt
is contextually benign or adversarial. For the first step, this could be done
using existing AI security solutions like guardrails to detect and protect the
LLMs. Guardrails have been developed using a variety of approaches. A popular
approach is to use signature based. Another popular approach to develop AI
models to classify such prompts include the use of NLP based models like a
language model. However, in the context of conducting an AI security
investigation of prompt injects, these guardrails lack the ability to aid
investigators in triaging or assessing the identified input prompts. In this
applied research exploration, we explore the use of a text generation
capabilities of LLM to detect prompt injects and generate explanation for its
detections to aid AI security investigators in assessing and triaging of such
prompt inject detections. The practical benefit of such a tool is to ease the
task of conducting investigation into prompt injects.
