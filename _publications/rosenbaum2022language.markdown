---
layout: publication
title: LINGUIST Language Model Instruction Tuning To Generate Annotated Utterances For Intent Classification And Slot Tagging
authors: Rosenbaum Andy, Soltan Saleh, Hamza Wael, Versley Yannick, Boese Markus
conference: "Arxiv"
year: 2022
bibkey: rosenbaum2022language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.09900"}
tags: ['Agentic', 'Applications', 'Prompting']
---
We present LINGUIST a method for generating annotated data for Intent Classification and Slot Tagging (IC+ST) via fine45;tuning AlexaTM 5B a 545;billion45;parameter multilingual sequence45;to45;sequence (seq2seq) model on a flexible instruction prompt. In a 1045;shot novel intent setting for the SNIPS dataset LINGUIST surpasses state45;of45;the45;art approaches (Back45;Translation and Example Extrapolation) by a wide margin showing absolute improvement for the target intents of +1.9 points on IC Recall and +2.5 points on ST F1 Score. In the zero45;shot cross45;lingual setting of the mATIS++ dataset LINGUIST out45;performs a strong baseline of Machine Translation with Slot Alignment by +4.14 points absolute on ST F1 Score across 6 languages while matching performance on IC. Finally we verify our results on an internal large45;scale multilingual dataset for conversational agent IC+ST and show significant improvements over a baseline which uses Back45;Translation Paraphrasing and Slot Catalog Resampling. To our knowledge we are the first to demonstrate instruction fine45;tuning of a large45;scale seq2seq model to control the outputs of multilingual intent45; and slot45;labeled data generation.
