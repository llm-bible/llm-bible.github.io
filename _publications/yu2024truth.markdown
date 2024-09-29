---
layout: publication
title: "Truth-aware Context Selection: Mitigating Hallucinations Of Large Language Models Being Misled By Untruthful Contexts"
authors: Yu Tian, Zhang Shaolei, Feng Yang
conference: "Arxiv"
year: 2024
bibkey: yu2024truth
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.07556"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'RAG', 'Tools']
---
Although Large Language Models (LLMs) have demonstrated impressive text generation capabilities they are easily misled by untruthful contexts provided by users or knowledge augmentation tools leading to hallucinations. To alleviate LLMs from being misled by untruthful context and take advantage of knowledge augmentation we propose Truth-Aware Context Selection (TACS) a lightweight method to adaptively recognize and mask untruthful context from the inputs. TACS begins by performing truth detection on the input context leveraging the parameterized knowledge within the LLM. Subsequently it constructs a corresponding attention mask based on the truthfulness of each position selecting the truthful context and discarding the untruthful context. Additionally we introduce a new evaluation metric Disturbance Adaption Rate to further study the LLMs ability to accept truthful information and resist untruthful information. Experimental results indicate that TACS can effectively filter untruthful context and significantly improve the overall quality of LLMs responses when presented with misleading information.
