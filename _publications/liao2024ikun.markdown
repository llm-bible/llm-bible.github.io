---
layout: publication
title: 'IKUN For WMT24 General MT Task: Llms Are Here For Multilingual Machine Translation'
authors: Liao Baohao, Herold Christian, Khadivi Shahram, Monz Christof
conference: "Arxiv"
year: 2024
bibkey: liao2024ikun
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11512"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Security', 'Training Techniques']
---
This paper introduces two multilingual systems, IKUN and IKUN-C, developed for the general machine translation task in WMT24. IKUN and IKUN-C represent an open system and a constrained system, respectively, built on Llama-3-8b and Mistral-7B-v0.3. Both systems are designed to handle all 11 language directions using a single model. According to automatic evaluation metrics, IKUN-C achieved 6 first-place and 3 second-place finishes among all constrained systems, while IKUN secured 1 first-place and 2 second-place finishes across both open and constrained systems. These encouraging results suggest that large language models (LLMs) are nearing the level of proficiency required for effective multilingual machine translation. The systems are based on a two-stage approach: first, continuous pre-training on monolingual data in 10 languages, followed by fine-tuning on high-quality parallel data for 11 language directions. The primary difference between IKUN and IKUN-C lies in their monolingual pre-training strategy. IKUN-C is pre-trained using constrained monolingual data, whereas IKUN leverages monolingual data from the OSCAR dataset. In the second phase, both systems are fine-tuned on parallel data sourced from NTREX, Flores, and WMT16-23 for all 11 language pairs.
