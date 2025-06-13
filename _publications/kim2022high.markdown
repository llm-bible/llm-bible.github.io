---
layout: publication
title: 'High Recall Data-to-text Generation With Progressive Edit'
authors: Choonghan Kim, Gary Geunbae Lee
conference: "Arxiv"
year: 2022
bibkey: kim2022high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.04558"}
tags: ['Model Architecture', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Applications']
---
Data-to-text (D2T) generation is the task of generating texts from structured
inputs. We observed that when the same target sentence was repeated twice,
Transformer (T5) based model generates an output made up of asymmetric
sentences from structured inputs. In other words, these sentences were
different in length and quality. We call this phenomenon "Asymmetric
Generation" and we exploit this in D2T generation. Once asymmetric sentences
are generated, we add the first part of the output with a no-repeated-target.
As this goes through progressive edit (ProEdit), the recall increases. Hence,
this method better covers structured inputs than before editing. ProEdit is a
simple but effective way to improve performance in D2T generation and it
achieves the new stateof-the-art result on the ToTTo dataset
