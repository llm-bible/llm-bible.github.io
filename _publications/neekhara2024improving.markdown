---
layout: publication
title: Improving Robustness of LLM-based Speech Synthesis by Learning Monotonic Alignment
authors: Neekhara Paarth, Hussain Shehzeen, Ghosh Subhankar, Li Jason, Valle Rafael, Badlani Rohan, Ginsburg Boris
conference: "Arxiv"
year: 2024
bibkey: neekhara2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17957"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Security', 'Training Techniques', 'Transformer']
---
Large Language Model (LLM) based text-to-speech (TTS) systems have demonstrated remarkable capabilities in handling large speech datasets and generating natural speech for new speakers. However LLM-based TTS models are not robust as the generated output can contain repeating words missing words and mis-aligned speech (referred to as hallucinations or attention errors) especially when the text contains multiple occurrences of the same token. We examine these challenges in an encoder-decoder transformer model and find that certain cross-attention heads in such models implicitly learn the text and speech alignment when trained for predicting speech tokens for a given text. To make the alignment more robust we propose techniques utilizing CTC loss and attention priors that encourage monotonic cross-attention over the text tokens. Our guided attention training technique does not introduce any new learnable parameters and significantly improves robustness of LLM-based TTS models.
