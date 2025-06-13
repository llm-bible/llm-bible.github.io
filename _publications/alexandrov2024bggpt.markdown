---
layout: publication
title: 'Bggpt 1.0: Extending English-centric Llms To Other Languages'
authors: Anton Alexandrov, Veselin Raychev, Dimitar I. Dimitrov, Ce Zhang, Martin Vechev, Kristina Toutanova
conference: "Arxiv"
year: 2024
bibkey: alexandrov2024bggpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10893"}
tags: ['Fine-Tuning', 'Responsible AI', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
We present BgGPT-Gemma-2-27B-Instruct and BgGPT-Gemma-2-9B-Instruct:
continually pretrained and fine-tuned versions of Google's Gemma-2 models,
specifically optimized for Bulgarian language understanding and generation.
Leveraging Gemma-2's multilingual capabilities and over 100 billion tokens of
Bulgarian and English text data, our models demonstrate strong performance in
Bulgarian language tasks, setting a new standard for language-specific AI
models. Our approach maintains the robust capabilities of the original Gemma-2
models, ensuring that the English language performance remains intact. To
preserve the base model capabilities, we incorporate continual learning
strategies based on recent Branch-and-Merge techniques as well as thorough
curation and selection of training data. We provide detailed insights into our
methodology, including the release of model weights with a commercial-friendly
license, enabling broader adoption by researchers, companies, and hobbyists.
Further, we establish a comprehensive set of benchmarks based on non-public
educational data sources to evaluate models on Bulgarian language tasks as well
as safety and chat capabilities. Our findings demonstrate the effectiveness of
fine-tuning state-of-the-art models like Gemma 2 to enhance language-specific
AI applications while maintaining cross-lingual capabilities.
