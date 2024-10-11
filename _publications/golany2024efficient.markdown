---
layout: publication
title: 'Efficient Data Generation For Source-grounded Information-seeking Dialogs: A Use Case For Meeting Transcripts'
authors: Golany Lotem, Galgani Filippo, Mamo Maya, Parasol Nimrod, Vandsburger Omer, Bar Nadav, Dagan Ido
conference: "Arxiv"
year: 2024
bibkey: golany2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01121"}
tags: ['Uncategorized']
---
Automating data generation with Large Language Models (LLMs) has become increasingly popular. In this work, we investigate the feasibility and effectiveness of LLM-based data generation in the challenging setting of source-grounded information-seeking dialogs, with response attribution, over long documents. Our source texts consist of long and noisy meeting transcripts, adding to the task complexity. Since automating attribution remains difficult, we propose a semi-automatic approach: dialog queries and responses are generated with LLMs, followed by human verification and identification of attribution spans. Using this approach, we created MISeD -- Meeting Information Seeking Dialogs dataset -- a dataset of information-seeking dialogs focused on meeting transcripts. Models finetuned with MISeD demonstrate superior performance compared to off-the-shelf models, even those of larger size. Finetuning on MISeD gives comparable response generation quality to finetuning on fully manual data, while improving attribution quality and reducing time and effort.
