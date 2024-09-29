---
layout: publication
title: Using Natural Language Explanations To Improve Robustness Of In45;context Learning
authors: He Xuanli, Wu Yuxiang, Camburu Oana-maria, Minervini Pasquale, Stenetorp Pontus
conference: "Arxiv"
year: 2023
bibkey: he2023using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07556"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Security']
---
Recent studies demonstrated that large language models (LLMs) can excel in many tasks via in45;context learning (ICL). However recent works show that ICL45;prompted models tend to produce inaccurate results when presented with adversarial inputs. In this work we investigate whether augmenting ICL with natural language explanations (NLEs) improves the robustness of LLMs on adversarial datasets covering natural language inference and paraphrasing identification. We prompt LLMs with a small set of human45;generated NLEs to produce further NLEs yielding more accurate results than both a zero45;shot45;ICL setting and using only human45;generated NLEs. Our results on five popular LLMs (GPT3.545;turbo Llama2 Vicuna Zephyr and Mistral) show that our approach yields over 637; improvement over baseline approaches for eight adversarial datasets HANS ISCS NaN ST PICD PISP ANLI and PAWS. Furthermore previous studies have demonstrated that prompt selection strategies significantly enhance ICL on in45;distribution test sets. However our findings reveal that these strategies do not match the efficacy of our approach for robustness evaluations resulting in an accuracy drop of 837; compared to the proposed approach.
