---
layout: publication
title: Multilingual Instruction Tuning With Just A Pinch Of Multilinguality
authors: Shaham Uri, Herzig Jonathan, Aharoni Roee, Szpektor Idan, Tsarfaty Reut, Eyal Matan
conference: "Arxiv"
year: 2024
bibkey: shaham2024multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.01854"}
tags: ['Pretraining Methods', 'Training Techniques']
---
As instruction45;tuned large language models (LLMs) gain global adoption their ability to follow instructions in multiple languages becomes increasingly crucial. In this work we investigate how multilinguality during instruction tuning of a multilingual LLM affects instruction45;following across languages from the pre45;training corpus. We first show that many languages transfer some instruction45;following capabilities to other languages from even monolingual tuning. Furthermore we find that only 40 multilingual examples integrated in an English tuning set substantially improve multilingual instruction45;following both in seen and unseen languages during tuning. In general we observe that models tuned on multilingual mixtures exhibit comparable or superior performance in multiple languages compared to monolingually tuned models despite training on 10x fewer examples in those languages. Finally we find that diversifying the instruction tuning set with even just 245;4 languages significantly improves cross45;lingual generalization. Our results suggest that building massively multilingual instruction45;tuned models can be done with only a very small set of multilingual instruction45;responses.
