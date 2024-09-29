---
layout: publication
title: On Measuring Faithfulness Or Self45;consistency Of Natural Language Explanations
authors: Parcalabescu Letitia, Frank Anette
conference: "Arxiv"
year: 2023
bibkey: parcalabescu2023measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07466"}
  - {name: "Code", url: "https://github.com/Heidelberg&#45;NLP/CC&#45;SHAP&#125;"}
tags: ['Has Code', 'Interpretability And Explainability', 'Reinforcement Learning']
---
Large language models (LLMs) can explain their predictions through post45;hoc or Chain45;of45;Thought (CoT) explanations. But an LLM could make up reasonably sounding explanations that are unfaithful to its underlying reasoning. Recent work has designed tests that aim to judge the faithfulness of post45;hoc or CoT explanations. In this work we argue that these faithfulness tests do not measure faithfulness to the models inner workings 45;45; but rather their self45;consistency at output level. Our contributions are three45;fold i) We clarify the status of faithfulness tests in view of model explainability characterising them as self45;consistency tests instead. This assessment we underline by ii) constructing a Comparative Consistency Bank for self45;consistency tests that for the first time compares existing tests on a common suite of 11 open LLMs and 5 tasks 45;45; including iii) our new self45;consistency measure CC45;SHAP. CC45;SHAP is a fine45;grained measure (not a test) of LLM self45;consistency. It compares how a models input contributes to the predicted answer and to generating the explanation. Our fine45;grained CC45;SHAP metric allows us iii) to compare LLM behaviour when making predictions and to analyse the effect of other consistency tests at a deeper level which takes us one step further towards measuring faithfulness by bringing us closer to the internals of the model than strictly surface output45;oriented tests. Our code is available at url123;https://github.com/Heidelberg&#45;NLP/CC&#45;SHAP&#125;
