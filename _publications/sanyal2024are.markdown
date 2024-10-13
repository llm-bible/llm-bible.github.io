---
layout: publication
title: 'Are Machines Better At Complex Reasoning? Unveiling Human-machine Inference Gaps In Entailment Verification'
authors: Sanyal Soumya, Xiao Tianyi, Liu Jiacheng, Wang Wenya, Ren Xiang
conference: "Arxiv"
year: 2024
bibkey: sanyal2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03686"}
tags: ['GPT', 'Model Architecture', 'RAG', 'Training Techniques', 'Uncategorized']
---
Making inferences in text comprehension to understand the meaning is
essential in language processing. This work studies the entailment verification
(EV) problem of multi-sentence premises that requires a system to make multiple
inferences implicitly. Studying EV for such complex premises is important
because modern NLP problems, such as detecting inconsistent model-generated
rationales, require complex multi-hop reasoning. However, current textual
inference datasets mostly contain short premises that only partially focus on
these challenges. To address this, we compile an EV benchmark that includes
datasets from three NLP domains (NLI, contextual QA, and rationales) containing
multi-sentence premises. On benchmarking humans and LLMs, we find that LLMs are
better than humans in multi-hop reasoning across extended contexts, while
humans perform better in simple deductive reasoning tasks. We also finetune a
Flan-T5 model for EV using two training objectives to obtain a strong
open-source model that outperforms GPT-3.5 and rivals GPT-4. Finally, we use
this model to filter out inconsistent model-generated rationales in
self-consistency decoding, resulting in a 6% accuracy improvement on average
across three MCQ datasets.
