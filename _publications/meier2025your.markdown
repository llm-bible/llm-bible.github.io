---
layout: publication
title: 'Trojanstego: Your Language Model Can Secretly Be A Steganographic Privacy Leaking Agent'
authors: Dominik Meier, Jan Philip Wahle, Paul Röttger, Terry Ruas, Bela Gipp
conference: "Arxiv"
year: 2025
bibkey: meier2025your
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20118'}
tags: ['Agentic', 'Security', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
As large language models (LLMs) become integrated into sensitive workflows, concerns grow over their potential to leak confidential information. We propose TrojanStego, a novel threat model in which an adversary fine-tunes an LLM to embed sensitive context information into natural-looking outputs via linguistic steganography, without requiring explicit control over inference inputs. We introduce a taxonomy outlining risk factors for compromised LLMs, and use it to evaluate the risk profile of the threat. To implement TrojanStego, we propose a practical encoding scheme based on vocabulary partitioning learnable by LLMs via fine-tuning. Experimental results show that compromised models reliably transmit 32-bit secrets with 87% accuracy on held-out prompts, reaching over 97% accuracy using majority voting across three generations. Further, they maintain high utility, can evade human detection, and preserve coherence. These results highlight a new class of LLM data exfiltration attacks that are passive, covert, practical, and dangerous.
