---
layout: publication
title: Improving Robustness Of Llm45;based Speech Synthesis By Learning Monotonic Alignment
authors: Neekhara Paarth, Hussain Shehzeen, Ghosh Subhankar, Li Jason, Valle Rafael, Badlani Rohan, Ginsburg Boris
conference: "Arxiv"
year: 2024
bibkey: neekhara2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17957"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Security', 'Training Techniques', 'Transformer']
---
Large Language Model (LLM) based text45;to45;speech (TTS) systems have demonstrated remarkable capabilities in handling large speech datasets and generating natural speech for new speakers. However LLM45;based TTS models are not robust as the generated output can contain repeating words missing words and mis45;aligned speech (referred to as hallucinations or attention errors) especially when the text contains multiple occurrences of the same token. We examine these challenges in an encoder45;decoder transformer model and find that certain cross45;attention heads in such models implicitly learn the text and speech alignment when trained for predicting speech tokens for a given text. To make the alignment more robust we propose techniques utilizing CTC loss and attention priors that encourage monotonic cross45;attention over the text tokens. Our guided attention training technique does not introduce any new learnable parameters and significantly improves robustness of LLM45;based TTS models.
