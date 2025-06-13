---
layout: publication
title: 'Viscon-100k: Leveraging Contextual Web Data For Fine-tuning Vision Language Models'
authors: Gokul Karthik Kumar, Iheb Chaabane, Kebin Wu
conference: "Arxiv"
year: 2025
bibkey: kumar2025viscon
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.10250"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Vision-language models (VLMs) excel in various visual benchmarks but are
often constrained by the lack of high-quality visual fine-tuning data. To
address this challenge, we introduce VisCon-100K, a novel dataset derived from
interleaved image-text web documents. Our approach transforms 45K web documents
from the OBELICS dataset into 100K image conversation samples. We utilize
GPT-4V to generate image-contextual captions and OpenChat 3.5 model to convert
these captions into diverse free-form and multiple-choice question-answer
pairs. Integrating this dataset for fine-tuning considerably enhances VLM
performance across multiple benchmarks. Unlike methods that focus solely on
fine-grained visual content, our approach leverages accompanying web context,
yielding superior results. We also discover that a 'leaky modality mix', where
conversation samples contain questions answerable from both the image and its
contextual caption, outperforms non-leaky combinations of captions and Q&A
pairs. VisCon-100k dataset shows strong performance with two popular VLM
approaches: text-only large language model (LLM) aligned with a vision encoder
using image captions data (ShareGPT4V-7b) and multimodally pretrained LLM
(IDEFICS2-8b) using interleaved image-text data. In addition to releasing the
VisCon-100K dataset, we provide a contextual captioner trained on this dataset,
facilitating scalable fine-tuning data generation for future research and
open-source applications. Using the same pipeline, but substituting our trained
contextual captioner for GPT-4V, we also release the larger VisCon-1M dataset.
