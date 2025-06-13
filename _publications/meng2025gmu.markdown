---
layout: publication
title: 'GMU Systems For The IWSLT 2025 Low-resource Speech Translation Shared Task'
authors: Chutong Meng, Antonios Anastasopoulos
conference: "Arxiv"
year: 2025
bibkey: meng2025gmu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21781"}
tags: ['Fine-Tuning', 'INTERSPEECH', 'Applications', 'Training Techniques', 'Pretraining Methods', 'SLT']
---
This paper describes the GMU systems for the IWSLT 2025 low-resource speech translation shared task. We trained systems for all language pairs, except for Levantine Arabic. We fine-tuned SeamlessM4T-v2 for automatic speech recognition (ASR), machine translation (MT), and end-to-end speech translation (E2E ST). The ASR and MT models are also used to form cascaded ST systems. Additionally, we explored various training paradigms for E2E ST fine-tuning, including direct E2E fine-tuning, multi-task training, and parameter initialization using components from fine-tuned ASR and/or MT models. Our results show that (1) direct E2E fine-tuning yields strong results; (2) initializing with a fine-tuned ASR encoder improves ST performance on languages SeamlessM4T-v2 has not been trained on; (3) multi-task training can be slightly helpful.
