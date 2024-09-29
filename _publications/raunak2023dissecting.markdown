---
layout: publication
title: Dissecting In-Context Learning of Translations in GPTs
authors: Raunak Vikas, Awadalla Hany Hassan, Menezes Arul
conference: "Arxiv"
year: 2023
bibkey: raunak2023dissecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15987"}
tags: ['Applications', 'Few Shot', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG']
---
Most of the recent work in leveraging Large Language Models (LLMs) such as GPT-3 for Machine Translation (MT) has focused on selecting the few-shot samples for prompting. In this work we try to better understand the role of demonstration attributes for the in-context learning of translations through perturbations of high-quality in-domain demonstrations. We find that asymmetric perturbation of the source-target mappings yield vastly different results. We show that the perturbation of the source side has surprisingly little impact while target perturbation can drastically reduce translation quality suggesting that it is the output text distribution that provides the most important learning signal during in-context learning of translations. We propose a method named Zero-Shot-Context to add this signal automatically in Zero-Shot prompting. We demonstrate that it improves upon the zero-shot translation performance of GPT-3 even making it competitive with few-shot prompted translations.
