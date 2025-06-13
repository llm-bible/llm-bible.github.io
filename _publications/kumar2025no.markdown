---
layout: publication
title: 'No Free Lunch With Guardrails'
authors: Divyanshu Kumar, Nitin Aravind Birur, Tanay Baswa, Sahil Agarwal, Prashanth Harshangi
conference: "Arxiv"
year: 2025
bibkey: kumar2025no
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.00441"}
tags: ['Responsible AI', 'Tools', 'GPT', 'Model Architecture', 'Security', 'Prompting']
---
As large language models (LLMs) and generative AI become widely adopted,
guardrails have emerged as a key tool to ensure their safe use. However, adding
guardrails isn't without tradeoffs; stronger security measures can reduce
usability, while more flexible systems may leave gaps for adversarial attacks.
In this work, we explore whether current guardrails effectively prevent misuse
while maintaining practical utility. We introduce a framework to evaluate these
tradeoffs, measuring how different guardrails balance risk, security, and
usability, and build an efficient guardrail.
  Our findings confirm that there is no free lunch with guardrails;
strengthening security often comes at the cost of usability. To address this,
we propose a blueprint for designing better guardrails that minimize risk while
maintaining usability. We evaluate various industry guardrails, including Azure
Content Safety, Bedrock Guardrails, OpenAI's Moderation API, Guardrails AI,
Nemo Guardrails, and Enkrypt AI guardrails. Additionally, we assess how LLMs
like GPT-4o, Gemini 2.0-Flash, Claude 3.5-Sonnet, and Mistral Large-Latest
respond under different system prompts, including simple prompts, detailed
prompts, and detailed prompts with chain-of-thought (CoT) reasoning. Our study
provides a clear comparison of how different guardrails perform, highlighting
the challenges in balancing security and usability.
