---
layout: publication
title: XRJL45;HKUST At Semeval45;2021 Task 4 Wordnet45;enhanced Dual Multi45;head Co45;attention For Reading Comprehension Of Abstract Meaning
authors: Jiang Yuxin, Shou Ziyi, Wang Qijun, Wu Hao, Lin Fangzhen
conference: "Arxiv"
year: 2021
bibkey: jiang2021xrjl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.16102"}
tags: ['Attention Mechanism', 'Model Architecture']
---
This paper presents our submitted system to SemEval 2021 Task 4 Reading Comprehension of Abstract Meaning. Our system uses a large pre45;trained language model as the encoder and an additional dual multi45;head co45;attention layer to strengthen the relationship between passages and question45;answer pairs following the current state45;of45;the45;art model DUMA. The main difference is that we stack the passage45;question and question45;passage attention modules instead of calculating parallelly to simulate re45;considering process. We also add a layer normalization module to improve the performance of our model. Furthermore to incorporate our known knowledge about abstract concepts we retrieve the definitions of candidate answers from WordNet and feed them to the model as extra inputs. Our system called WordNet45;enhanced DUal Multi45;head Co45;Attention (WN45;DUMA) achieves 86.6737; and 89.9937; accuracy on the official blind test set of subtask 1 and subtask 2 respectively.
