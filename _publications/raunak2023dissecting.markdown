---
layout: publication
title: Dissecting In45;context Learning Of Translations In Gpts
authors: Raunak Vikas, Awadalla Hany Hassan, Menezes Arul
conference: "Arxiv"
year: 2023
bibkey: raunak2023dissecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15987"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG']
---
Most of the recent work in leveraging Large Language Models (LLMs) such as GPT45;3 for Machine Translation (MT) has focused on selecting the few45;shot samples for prompting. In this work we try to better understand the role of demonstration attributes for the in45;context learning of translations through perturbations of high45;quality in45;domain demonstrations. We find that asymmetric perturbation of the source45;target mappings yield vastly different results. We show that the perturbation of the source side has surprisingly little impact while target perturbation can drastically reduce translation quality suggesting that it is the output text distribution that provides the most important learning signal during in45;context learning of translations. We propose a method named Zero45;Shot45;Context to add this signal automatically in Zero45;Shot prompting. We demonstrate that it improves upon the zero45;shot translation performance of GPT45;3 even making it competitive with few45;shot prompted translations.
