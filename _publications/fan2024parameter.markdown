---
layout: publication
title: 'Fedcollm: A Parameter-efficient Federated Co-tuning Framework For Large And Small Language Models'
authors: Tao Fan, Yan Kang, Guoqiang Ma, Lixin Fan, Kai Chen, Qiang Yang
conference: "Arxiv"
year: 2024
bibkey: fan2024parameter
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.11707'}
tags: ['Language Modeling', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
By adapting Large Language Models (LLMs) to domain-specific tasks or
enriching them with domain-specific knowledge, we can fully harness the
capabilities of LLMs. Nonetheless, a gap persists in achieving simultaneous
mutual enhancement between the server's LLM and the downstream clients' Small
Language Models (SLMs). To address this, we propose FedCoLLM, a novel and
parameter-efficient federated framework designed for co-tuning LLMs and SLMs.
This approach is aimed at adaptively transferring server-side LLMs knowledge to
clients' SLMs while simultaneously enriching the LLMs with domain insights from
the clients. To accomplish this, FedCoLLM utilizes lightweight adapters in
conjunction with SLMs, facilitating knowledge exchange between server and
clients in a manner that respects data privacy while also minimizing
computational and communication overhead. Our evaluation of FedCoLLM, utilizing
various public LLMs and SLMs across a range of NLP text generation tasks,
reveals that the performance of clients' SLMs experiences notable improvements
with the assistance of the LLMs. Simultaneously, the LLMs enhanced via FedCoLLM
achieves comparable performance to that obtained through direct fine-tuning on
clients' data.
