---
layout: publication
title: 'Improving The Robustness Of Transformer-based Large Language Models With Dynamic Attention'
authors: Lujia Shen, Yuwen Pu, Shouling Ji, Changjiang Li, Xuhong Zhang, Chunpeng Ge, Ting Wang
conference: "Arxiv"
year: 2023
bibkey: shen2023improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.17400'}
tags: ['Attention Mechanism', 'Transformer', 'Security', 'Training Techniques', 'BERT', 'Model Architecture', 'GPT', 'Pretraining Methods']
---
Transformer-based models, such as BERT and GPT, have been widely adopted in
natural language processing (NLP) due to their exceptional performance.
However, recent studies show their vulnerability to textual adversarial attacks
where the model's output can be misled by intentionally manipulating the text
inputs. Despite various methods that have been proposed to enhance the model's
robustness and mitigate this vulnerability, many require heavy consumption
resources (e.g., adversarial training) or only provide limited protection
(e.g., defensive dropout). In this paper, we propose a novel method called
dynamic attention, tailored for the transformer architecture, to enhance the
inherent robustness of the model itself against various adversarial attacks.
Our method requires no downstream task knowledge and does not incur additional
costs. The proposed dynamic attention consists of two modules: (I) attention
rectification, which masks or weakens the attention value of the chosen tokens,
and (ii) dynamic modeling, which dynamically builds the set of candidate
tokens. Extensive experiments demonstrate that dynamic attention significantly
mitigates the impact of adversarial attacks, improving up to 33% better
performance than previous methods against widely-used adversarial attacks. The
model-level design of dynamic attention enables it to be easily combined with
other defense methods (e.g., adversarial training) to further enhance the
model's robustness. Furthermore, we demonstrate that dynamic attention
preserves the state-of-the-art robustness space of the original model compared
to other dynamic modeling methods.
