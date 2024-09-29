---
layout: publication
title: Goat Fine45;tuned Llama Outperforms GPT45;4 On Arithmetic Tasks
authors: Liu Tiedong, Low Bryan Kian Hsiang
conference: "Arxiv"
year: 2023
bibkey: liu2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14201"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'RAG', 'Tokenization']
---
We introduce Goat a fine45;tuned LLaMA model that significantly outperforms GPT45;4 on a range of arithmetic tasks. Fine45;tuned on a synthetically generated dataset Goat achieves state45;of45;the45;art performance on BIG45;bench arithmetic sub45;task. In particular the zero45;shot Goat45;7B matches or even surpasses the accuracy achieved by the few45;shot PaLM45;540B. Surprisingly Goat can achieve near45;perfect accuracy on large45;number addition and subtraction through supervised fine45;tuning only which is almost impossible with previous pretrained language models such as Bloom OPT GPT45;NeoX etc. We attribute Goats exceptional performance to LLaMAs consistent tokenization of numbers. To tackle more challenging tasks like large45;number multiplication and division we propose an approach that classifies tasks based on their learnability and subsequently decomposes unlearnable tasks such as multi45;digit multiplication and division into a series of learnable tasks by leveraging basic arithmetic principles. We thoroughly examine the performance of our model offering a comprehensive evaluation of the effectiveness of our proposed decomposition steps. Additionally Goat45;7B can be easily trained using LoRA on a 24GB VRAM GPU facilitating reproducibility for other researchers. We release our model dataset and the Python script for dataset generation.
