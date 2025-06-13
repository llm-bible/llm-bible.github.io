---
layout: publication
title: 'Dissecting In-context Learning Of Translations In Gpts'
authors: Vikas Raunak, Hany Hassan Awadalla, Arul Menezes
conference: "Arxiv"
year: 2023
bibkey: raunak2023dissecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15987"}
tags: ['GPT', 'Applications', 'RAG', 'Model Architecture', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Most of the recent work in leveraging Large Language Models (LLMs) such as
GPT-3 for Machine Translation (MT) has focused on selecting the few-shot
samples for prompting. In this work, we try to better understand the role of
demonstration attributes for the in-context learning of translations through
perturbations of high-quality, in-domain demonstrations. We find that
asymmetric perturbation of the source-target mappings yield vastly different
results. We show that the perturbation of the source side has surprisingly
little impact, while target perturbation can drastically reduce translation
quality, suggesting that it is the output text distribution that provides the
most important learning signal during in-context learning of translations. We
propose a method named Zero-Shot-Context to add this signal automatically in
Zero-Shot prompting. We demonstrate that it improves upon the zero-shot
translation performance of GPT-3, even making it competitive with few-shot
prompted translations.
