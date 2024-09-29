---
layout: publication
title: 'VBART: The Turkish LLM'
authors: Turker Meliksah, Ari Mehmet Erdi, Han Aydin
conference: "Arxiv"
year: 2024
bibkey: turker2024turkish
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01308"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Language Modeling', 'Masked Language Model', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
We present VBART the first Turkish sequence-to-sequence Large Language Models (LLMs) pre-trained on a large corpus from scratch. VBART are compact LLMs based on good ideas leveraged from BART and mBART models and come in two sizes Large and XLarge. Fine-tuned VBART models surpass the prior state-of-the-art results in abstractive text summarization title generation text paraphrasing question answering and question generation tasks. They allow fine-tuning for future text generation tasks and datasets carving a new path for Turkish Natural Language Processing (NLP) research. Our work shows that having a pre-trained LLM for Turkish outperforms up to 3x multilingual models improving existing results and providing efficient models for training and inference. Moreover we show that our monolingual tokenizer is up to 11x more efficient than multilingual tokenizers. Last but not least we introduce a method to enlarge an existing pre-trained LLM and question the relevancy of Chinchilla Scaling Law to sequence-to-sequence masked language models. Our fine-tuned models tokenizer and cleaned vngrs-web-corpus of 135 GB are publicly available at huggingface.co/vngrs-ai.
