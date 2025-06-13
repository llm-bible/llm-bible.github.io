---
layout: publication
title: 'Identifying And Analyzing Performance-critical Tokens In Large Language Models'
authors: Yu Bai, Heyan Huang, Cesare Spinoso-di Piano, Marc-antoine Rondeau, Sanxing Chen, Yang Gao, Jackie Chi Kit Cheung
conference: "Arxiv"
year: 2024
bibkey: bai2024identifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.11323'}
tags: ['Attention Mechanism', 'Few-Shot', 'RAG', 'Model Architecture', 'Prompting', 'In-Context Learning']
---
In-context learning (ICL) has emerged as an effective solution for few-shot
learning with large language models (LLMs). However, how LLMs leverage
demonstrations to specify a task and learn a corresponding computational
function through ICL is underexplored. Drawing from the way humans learn from
content-label mappings in demonstrations, we categorize the tokens in an ICL
prompt into content, stopword, and template tokens. Our goal is to identify the
types of tokens whose representations directly influence LLM's performance, a
property we refer to as being performance-critical. By ablating representations
from the attention of the test example, we find that the representations of
informative content tokens have less influence on performance compared to
template and stopword tokens, which contrasts with the human attention to
informative words. We give evidence that the representations of
performance-critical tokens aggregate information from the content tokens.
Moreover, we demonstrate experimentally that lexical meaning, repetition, and
structural cues are the main distinguishing characteristics of these tokens.
Our work sheds light on how large language models learn to perform tasks from
demonstrations and deepens our understanding of the roles different types of
tokens play in large language models.
