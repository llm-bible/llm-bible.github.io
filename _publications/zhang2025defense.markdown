---
layout: publication
title: 'Defense Against Prompt Injection Attacks Via Mixture Of Encodings'
authors: Ruiyi Zhang, David Sullivan, Kyle Jackson, Pengtao Xie, Mei Chen
conference: "Arxiv"
year: 2025
bibkey: zhang2025defense
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07467"}
tags: ['Responsible AI', 'Security', 'Prompting']
---
Large Language Models (LLMs) have emerged as a dominant approach for a wide
range of NLP tasks, with their access to external information further enhancing
their capabilities. However, this introduces new vulnerabilities, known as
prompt injection attacks, where external content embeds malicious instructions
that manipulate the LLM's output. Recently, the Base64 defense has been
recognized as one of the most effective methods for reducing success rate of
prompt injection attacks. Despite its efficacy, this method can degrade LLM
performance on certain NLP tasks. To address this challenge, we propose a novel
defense mechanism: mixture of encodings, which utilizes multiple character
encodings, including Base64. Extensive experimental results show that our
method achieves one of the lowest attack success rates under prompt injection
attacks, while maintaining high performance across all NLP tasks, outperforming
existing character encoding-based defense methods. This underscores the
effectiveness of our mixture of encodings strategy for both safety and task
performance metrics.
