---
layout: publication
title: 'Helping Large Language Models Protect Themselves: An Enhanced Filtering And Summarization System'
authors: Sheikh Samit Muhaimin, Spyridon Mastorakis
conference: "Arxiv"
year: 2025
bibkey: muhaimin2025helping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01315"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
The recent growth in the use of Large Language Models has made them
vulnerable to sophisticated adversarial assaults, manipulative prompts, and
encoded malicious inputs. Existing countermeasures frequently necessitate
retraining models, which is computationally costly and impracticable for
deployment. Without the need for retraining or fine-tuning, this study presents
a unique defense paradigm that allows LLMs to recognize, filter, and defend
against adversarial or malicious inputs on their own. There are two main parts
to the suggested framework: (1) A prompt filtering module that uses
sophisticated Natural Language Processing (NLP) techniques, including zero-shot
classification, keyword analysis, and encoded content detection (e.g. base64,
hexadecimal, URL encoding), to detect, decode, and classify harmful inputs; and
(2) A summarization module that processes and summarizes adversarial research
literature to give the LLM context-aware defense knowledge. This approach
strengthens LLMs' resistance to adversarial exploitation by fusing text
extraction, summarization, and harmful prompt analysis. According to
experimental results, this integrated technique has a 98.71% success rate in
identifying harmful patterns, manipulative language structures, and encoded
prompts. By employing a modest amount of adversarial research literature as
context, the methodology also allows the model to react correctly to harmful
inputs with a larger percentage of jailbreak resistance and refusal rate. While
maintaining the quality of LLM responses, the framework dramatically increases
LLM's resistance to hostile misuse, demonstrating its efficacy as a quick and
easy substitute for time-consuming, retraining-based defenses.
