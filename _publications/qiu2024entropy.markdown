---
layout: publication
title: Entropy45;based Decoding For Retrieval45;augmented Large Language Models
authors: Qiu Zexuan, Ou Zijing, Wu Bin, Li Jingjing, Liu Aiwei, King Irwin
conference: "Arxiv"
year: 2024
bibkey: qiu2024entropy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17519"}
tags: ['Applications', 'Training Techniques']
---
Augmenting Large Language Models (LLMs) with retrieved external knowledge has proven effective for improving the factual accuracy of generated responses. Despite their success retrieval45;augmented LLMs still face the distractibility issue where the generated responses are negatively influenced by noise from both external and internal knowledge sources. In this paper we introduce a novel training45;free decoding method guided by entropy considerations to mitigate this issue. Our approach utilizes entropy45;based document45;parallel ensemble decoding to prioritize low45;entropy distributions from retrieved documents thereby enhancing the extraction of relevant information of context. Additionally it incorporates a contrastive decoding mechanism that contrasts the obtained low45;entropy ensemble distribution with the high45;entropy distribution derived from the models internal knowledge across layers which ensures a greater emphasis on reliable external information. Extensive experiments on open45;domain question answering datasets demonstrate the superiority of our method.
