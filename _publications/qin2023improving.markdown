---
layout: publication
title: "Improving In-context Learning Via Bidirectional Alignment"
authors: Qin Chengwei, Xia Wenhan, Jiao Fangkai, Chen Chen, Hu Yuchen, Ding Bosheng, Joty Shafiq
conference: "Arxiv"
year: 2023
bibkey: qin2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17055"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Few Shot', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG']
---
Large language models (LLMs) have shown impressive few-shot generalization on many tasks via in-context learning (ICL). Despite their success in showing such emergent abilities the scale and complexity of larger models also lead to unprecedentedly high computational demands and deployment challenges. In reaction researchers explore transferring the powerful capabilities of larger models to more efficient and compact models by typically aligning the output of smaller (student) models with that of larger (teacher) models. Existing methods either train student models on the generated outputs of teacher models or imitate their token-level probability distributions. However these distillation methods pay little to no attention to the input which also plays a crucial role in ICL. Based on the finding that the performance of ICL is highly sensitive to the selection of demonstration examples we propose Bidirectional Alignment (BiAlign) to fully leverage the models preferences for ICL examples to improve the ICL abilities of student models. Specifically we introduce the alignment of input preferences between student and teacher models by incorporating a novel ranking loss in addition to aligning the token-level output distribution. With extensive experiments and analysis we demonstrate that BiAlign can consistently outperform existing baselines on a variety of tasks involving language understanding reasoning and coding.
