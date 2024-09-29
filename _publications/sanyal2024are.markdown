---
layout: publication
title: Are Machines Better At Complex Reasoning Unveiling Human45;machine Inference Gaps In Entailment Verification
authors: Sanyal Soumya, Xiao Tianyi, Liu Jiacheng, Wang Wenya, Ren Xiang
conference: "Arxiv"
year: 2024
bibkey: sanyal2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03686"}
tags: ['GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Making inferences in text comprehension to understand the meaning is essential in language processing. This work studies the entailment verification (EV) problem of multi45;sentence premises that requires a system to make multiple inferences implicitly. Studying EV for such complex premises is important because modern NLP problems such as detecting inconsistent model45;generated rationales require complex multi45;hop reasoning. However current textual inference datasets mostly contain short premises that only partially focus on these challenges. To address this we compile an EV benchmark that includes datasets from three NLP domains (NLI contextual QA and rationales) containing multi45;sentence premises. On benchmarking humans and LLMs we find that LLMs are better than humans in multi45;hop reasoning across extended contexts while humans perform better in simple deductive reasoning tasks. We also finetune a Flan45;T5 model for EV using two training objectives to obtain a strong open45;source model that outperforms GPT45;3.5 and rivals GPT45;4. Finally we use this model to filter out inconsistent model45;generated rationales in self45;consistency decoding resulting in a 637; accuracy improvement on average across three MCQ datasets.
