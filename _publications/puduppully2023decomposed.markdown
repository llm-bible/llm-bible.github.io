---
layout: publication
title: Decomposed Prompting for Machine Translation Between Related Languages using Large Language Models
authors: Puduppully Ratish, Kunchukuttan Anoop, Dabre Raj, Aw Ai Ti, Chen Nancy F.
conference: "Arxiv"
year: 2023
bibkey: puduppully2023decomposed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13085"}
tags: ['Applications', 'Few Shot', 'In Context Learning', 'Prompting', 'RAG']
---
This study investigates machine translation between related languages i.e. languages within the same family that share linguistic characteristics such as word order and lexical similarity. Machine translation through few-shot prompting leverages a small set of translation pair examples to generate translations for test sentences. This procedure requires the model to learn how to generate translations while simultaneously ensuring that token ordering is maintained to produce a fluent and accurate translation. We propose that for related languages the task of machine translation can be simplified by leveraging the monotonic alignment characteristic of such languages. We introduce DecoMT a novel approach of few-shot prompting that decomposes the translation process into a sequence of word chunk translations. Through automatic and human evaluation conducted on multiple related language pairs across various language families we demonstrate that our proposed approach of decomposed prompting surpasses multiple established few-shot baseline approaches. For example DecoMT outperforms the strong few-shot prompting BLOOM model with an average improvement of 8 chrF++ scores across the examined languages.
