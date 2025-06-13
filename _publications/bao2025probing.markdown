---
layout: publication
title: 'Probing The Geometry Of Truth: Consistency And Generalization Of Truth Directions In Llms Across Logical Transformations And Question Answering Tasks'
authors: Yuntai Bao, Xuhong Zhang, Tianyu Du, Xinkui Zhao, Zhengwen Feng, Hao Peng, Jianwei Yin
conference: "Arxiv"
year: 2025
bibkey: bao2025probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00823"}
  - {name: "Code", url: "https://github.com/colored-dye/truthfulness_probe_generalization"}
tags: ['Applications', 'Reinforcement Learning', 'Has Code', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) are trained on extensive datasets that encapsulate substantial world knowledge. However, their outputs often include confidently stated inaccuracies. Earlier works suggest that LLMs encode truthfulness as a distinct linear feature, termed the "truth direction", which can classify truthfulness reliably. We address several open questions about the truth direction: (i) whether LLMs universally exhibit consistent truth directions; (ii) whether sophisticated probing techniques are necessary to identify truth directions; and (iii) how the truth direction generalizes across diverse contexts. Our findings reveal that not all LLMs exhibit consistent truth directions, with stronger representations observed in more capable models, particularly in the context of logical negation. Additionally, we demonstrate that truthfulness probes trained on declarative atomic statements can generalize effectively to logical transformations, question-answering tasks, in-context learning, and external knowledge sources. Finally, we explore the practical application of truthfulness probes in selective question-answering, illustrating their potential to improve user trust in LLM outputs. These results advance our understanding of truth directions and provide new insights into the internal representations of LLM beliefs. Our code is public at https://github.com/colored-dye/truthfulness_probe_generalization
