---
layout: publication
title: Progres Prompted Generative Rescoring On ASR N45;best
authors: Tur Ada Defne, Moumen Adel, Ravanelli Mirco
conference: "Arxiv"
year: 2024
bibkey: tur2024prompted
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00217"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
Large Language Models (LLMs) have shown their ability to improve the performance of speech recognizers by effectively rescoring the n45;best hypotheses generated during the beam search process. However the best way to exploit recent generative instruction45;tuned LLMs for hypothesis rescoring is still unclear. This paper proposes a novel method that uses instruction45;tuned LLMs to dynamically expand the n45;best speech recognition hypotheses with new hypotheses generated through appropriately45;prompted LLMs. Specifically we introduce a new zero45;shot method for ASR n45;best rescoring which combines confidence scores LLM sequence scoring and prompt45;based hypothesis generation. We compare Llama45;345;Instruct GPT45;3.5 Turbo and GPT45;4 Turbo as prompt45;based generators with Llama45;3 as sequence scorer LLM. We evaluated our approach using different speech recognizers and observed significant relative improvement in the word error rate (WER) ranging from 537; to 2537;.
