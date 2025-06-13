---
layout: publication
title: 'Entropy-based Decoding For Retrieval-augmented Large Language Models'
authors: Zexuan Qiu, Zijing Ou, Bin Wu, Jingjing Li, Aiwei Liu, Irwin King
conference: "Arxiv"
year: 2024
bibkey: qiu2024entropy
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.17519'}
tags: ['RAG', 'Applications', 'Training Techniques']
---
Augmenting Large Language Models (LLMs) with retrieved external knowledge has
proven effective for improving the factual accuracy of generated responses.
Despite their success, retrieval-augmented LLMs still face the distractibility
issue, where the generated responses are negatively influenced by noise from
both external and internal knowledge sources. In this paper, we introduce a
novel, training-free decoding method guided by entropy considerations to
mitigate this issue. Our approach utilizes entropy-based document-parallel
ensemble decoding to prioritize low-entropy distributions from retrieved
documents, thereby enhancing the extraction of relevant information of context.
Additionally, it incorporates a contrastive decoding mechanism that contrasts
the obtained low-entropy ensemble distribution with the high-entropy
distribution derived from the model's internal knowledge across layers, which
ensures a greater emphasis on reliable external information. Extensive
experiments on open-domain question answering datasets demonstrate the
superiority of our method.
