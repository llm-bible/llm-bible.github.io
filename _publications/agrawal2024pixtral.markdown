---
layout: publication
title: 'Pixtral 12B'
authors: Pravesh Agrawal, Szymon Antoniak, Emma Bou Hanna, Baptiste Bout, Devendra Chaplot, Jessica Chudnovsky, Diogo Costa, Baudouin De Monicault, Saurabh Garg, Theophile Gervet, Soham Ghosh, Amélie Héliou, Paul Jacob, Albert Q. Jiang, Kartik Khandelwal, Timothée Lacroix, Guillaume Lample, Diego Las Casas, Thibaut Lavril, Teven Le Scao, Andy Lo, William Marshall, Louis Martin, Arthur Mensch, Pavankumar Muddireddy, Valera Nemychnikova, Marie Pellat, Patrick Von Platen, Nikhil Raghuraman, Baptiste Rozière, Alexandre Sablayrolles, Lucile Saulnier, Romain Sauvestre, Wendy Shang, Roman Soletskyi, Lawrence Stewart, Pierre Stock, Joachim Studnia, Sandeep Subramanian, Sagar Vaze, Thomas Wang, Sophia Yang
conference: "Arxiv"
year: 2024
bibkey: agrawal2024pixtral
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.07073"}
tags: ['Multimodal Models']
---
We introduce Pixtral-12B, a 12--billion-parameter multimodal language model.
Pixtral-12B is trained to understand both natural images and documents,
achieving leading performance on various multimodal benchmarks, surpassing a
number of larger models. Unlike many open-source models, Pixtral is also a
cutting-edge text model for its size, and does not compromise on natural
language performance to excel in multimodal tasks. Pixtral uses a new vision
encoder trained from scratch, which allows it to ingest images at their natural
resolution and aspect ratio. This gives users flexibility on the number of
tokens used to process an image. Pixtral is also able to process any number of
images in its long context window of 128K tokens. Pixtral 12B substanially
outperforms other open models of similar sizes (Llama-3.2 11B \& Qwen-2-VL 7B).
It also outperforms much larger open models like Llama-3.2 90B while being 7x
smaller. We further contribute an open-source benchmark, MM-MT-Bench, for
evaluating vision-language models in practical scenarios, and provide detailed
analysis and code for standardized evaluation protocols for multimodal LLMs.
Pixtral-12B is released under Apache 2.0 license.
