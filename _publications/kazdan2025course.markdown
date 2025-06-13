---
layout: publication
title: 'No, Of Course I Can! Refusal Mechanisms Can Be Exploited Using Harmless Fine-tuning Data'
authors: Joshua Kazdan, Lisa Yu, Rylan Schaeffer, Chris Cundy, Sanmi Koyejo, Krishnamurthy Dvijotham
conference: "Arxiv"
year: 2025
bibkey: kazdan2025course
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19537"}
tags: ['Fine-Tuning', 'Responsible AI', 'Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Leading language model (LM) providers like OpenAI and Google offer
fine-tuning APIs that allow customers to adapt LMs for specific use cases. To
prevent misuse, these LM providers implement filtering mechanisms to block
harmful fine-tuning data. Consequently, adversaries seeking to produce unsafe
LMs via these APIs must craft adversarial training data that are not
identifiably harmful. We make three contributions in this context: 1. We show
that many existing attacks that use harmless data to create unsafe LMs rely on
eliminating model refusals in the first few tokens of their responses. 2. We
show that such prior attacks can be blocked by a simple defense that pre-fills
the first few tokens from an aligned model before letting the fine-tuned model
fill in the rest. 3. We describe a new data-poisoning attack, ``No, Of course I
Can Execute'' (NOICE), which exploits an LM's formulaic refusal mechanism to
elicit harmful responses. By training an LM to refuse benign requests on the
basis of safety before fulfilling those requests regardless, we are able to
jailbreak several open-source models and a closed-source model (GPT-4o). We
show an attack success rate (ASR) of 57% against GPT-4o; our attack earned a
Bug Bounty from OpenAI. Against open-source models protected by simple
defenses, we improve ASRs by an average of 3.25 times compared to the best
performing previous attacks that use only harmless data. NOICE demonstrates the
exploitability of repetitive refusal mechanisms and broadens understanding of
the threats closed-source models face from harmless data.
