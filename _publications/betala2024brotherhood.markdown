---
layout: publication
title: 'Brotherhood At WMT 2024: Leveraging Llm-generated Contextual Conversations For Cross-lingual Image Captioning'
authors: Siddharth Betala, Ishan Chokshi
conference: "Arxiv"
year: 2024
bibkey: betala2024brotherhood
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.15052"}
tags: ['WMT', 'Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
In this paper, we describe our system under the team name Brotherhood for the
English-to-Lowres Multi-Modal Translation Task. We participate in the
multi-modal translation tasks for English-Hindi, English-Hausa,
English-Bengali, and English-Malayalam language pairs. We present a method
leveraging multi-modal Large Language Models (LLMs), specifically GPT-4o and
Claude 3.5 Sonnet, to enhance cross-lingual image captioning without
traditional training or fine-tuning. Our approach utilizes instruction-tuned
prompting to generate rich, contextual conversations about cropped images,
using their English captions as additional context. These synthetic
conversations are then translated into the target languages. Finally, we employ
a weighted prompting strategy, balancing the original English caption with the
translated conversation to generate captions in the target language. This
method achieved competitive results, scoring 37.90 BLEU on the English-Hindi
Challenge Set and ranking first and second for English-Hausa on the Challenge
and Evaluation Leaderboards, respectively. We conduct additional experiments on
a subset of 250 images, exploring the trade-offs between BLEU scores and
semantic similarity across various weighting schemes.
