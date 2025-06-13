---
layout: publication
title: 'Phantom: General Trigger Attacks On Retrieval Augmented Language Generation'
authors: Harsh Chaudhari, Giorgio Severi, John Abascal, Matthew Jagielski, Christopher A. Choquette-choo, Milad Nasr, Cristina Nita-rotaru, Alina Oprea
conference: "Arxiv"
year: 2024
bibkey: chaudhari2024general
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.20485'}
tags: ['RAG', 'Efficiency and Optimization', 'Security', 'Model Architecture', 'Tools', 'Applications', 'Training Techniques', 'GPT', 'Reinforcement Learning']
---
Retrieval Augmented Generation (RAG) expands the capabilities of modern large
language models (LLMs), by anchoring, adapting, and personalizing their
responses to the most relevant knowledge sources. It is particularly useful in
chatbot applications, allowing developers to customize LLM output without
expensive retraining. Despite their significant utility in various
applications, RAG systems present new security risks. In this work, we propose
new attack vectors that allow an adversary to inject a single malicious
document into a RAG system's knowledge base, and mount a backdoor poisoning
attack. We design Phantom, a general two-stage optimization framework against
RAG systems, that crafts a malicious poisoned document leading to an integrity
violation in the model's output. First, the document is constructed to be
retrieved only when a specific trigger sequence of tokens appears in the
victim's queries. Second, the document is further optimized with crafted
adversarial text that induces various adversarial objectives on the LLM output,
including refusal to answer, reputation damage, privacy violations, and harmful
behaviors. We demonstrate our attacks on multiple LLM architectures, including
Gemma, Vicuna, and Llama, and show that they transfer to GPT-3.5 Turbo and
GPT-4. Finally, we successfully conducted a Phantom attack on NVIDIA's
black-box production RAG system, "Chat with RTX".
