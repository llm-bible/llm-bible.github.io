---
layout: publication
title: 'Fine-tuned ''small'' Llms (still) Significantly Outperform Zero-shot Generative AI Models In Text Classification'
authors: Martin Juan José Bucher, Marco Martini
conference: "Arxiv"
year: 2024
bibkey: bucher2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08660"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'BERT', 'Prompting']
---
Generative AI offers a simple, prompt-based alternative to fine-tuning
smaller BERT-style LLMs for text classification tasks. This promises to
eliminate the need for manually labeled training data and task-specific model
training. However, it remains an open question whether tools like ChatGPT can
deliver on this promise. In this paper, we show that smaller, fine-tuned LLMs
(still) consistently and significantly outperform larger, zero-shot prompted
models in text classification. We compare three major generative AI models
(ChatGPT with GPT-3.5/GPT-4 and Claude Opus) with several fine-tuned LLMs
across a diverse set of classification tasks (sentiment, approval/disapproval,
emotions, party positions) and text categories (news, tweets, speeches). We
find that fine-tuning with application-specific training data achieves superior
performance in all cases. To make this approach more accessible to a broader
audience, we provide an easy-to-use toolkit alongside this paper. Our toolkit,
accompanied by non-technical step-by-step guidance, enables users to select and
fine-tune BERT-like LLMs for any classification task with minimal technical and
computational effort.
