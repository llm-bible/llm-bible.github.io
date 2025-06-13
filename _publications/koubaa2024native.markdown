---
layout: publication
title: 'Arabiangpt: Native Arabic Gpt-based Large Language Model'
authors: Anis Koubaa, Adel Ammar, Lahouari Ghouti, Omar Najar, Serry Sibaee
conference: "Arxiv"
year: 2024
bibkey: koubaa2024native
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15313"}
tags: ['Fine-Tuning', 'Transformer', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
The predominance of English and Latin-based large language models (LLMs) has
led to a notable deficit in native Arabic LLMs. This discrepancy is accentuated
by the prevalent inclusion of English tokens in existing Arabic models,
detracting from their efficacy in processing native Arabic's intricate
morphology and syntax. Consequently, there is a theoretical and practical
imperative for developing LLMs predominantly focused on Arabic linguistic
elements. To address this gap, this paper proposes ArabianGPT, a series of
transformer-based models within the ArabianLLM suite designed explicitly for
Arabic. These models, including ArabianGPT-0.1B and ArabianGPT-0.3B, vary in
size and complexity, aligning with the nuanced linguistic characteristics of
Arabic. The AraNizer tokenizer, integral to these models, addresses the unique
morphological aspects of Arabic script, ensuring more accurate text processing.
Empirical results from fine-tuning the models on tasks like sentiment analysis
and summarization demonstrate significant improvements. For sentiment analysis,
the fine-tuned ArabianGPT-0.1B model achieved a remarkable accuracy of 95%, a
substantial increase from the base model's 56%. Similarly, in summarization
tasks, fine-tuned models showed enhanced F1 scores, indicating improved
precision and recall in generating concise summaries. Comparative analysis of
fine-tuned ArabianGPT models against their base versions across various
benchmarks reveals nuanced differences in performance, with fine-tuning
positively impacting specific tasks like question answering and summarization.
These findings underscore the efficacy of fine-tuning in aligning ArabianGPT
models more closely with specific NLP tasks, highlighting the potential of
tailored transformer architectures in advancing Arabic NLP.
