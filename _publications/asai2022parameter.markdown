---
layout: publication
title: ATTEMPT Parameter45;efficient Multi45;task Tuning Via Attentional Mixtures Of Soft Prompts
authors: Asai Akari, Salehi Mohammadreza, Peters Matthew E., Hajishirzi Hannaneh
conference: "Arxiv"
year: 2022
bibkey: asai2022parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.11961"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Prompting', 'Training Techniques']
---
This work introduces a new multi45;task parameter45;efficient language model (LM) tuning method that learns to transfer knowledge across different tasks via a mixture of soft prompts45;small prefix embedding vectors pre45;trained for different tasks. Our method called ATTEMPT (ATTEntional Mixtures of Prompt Tuning) obtains source prompts as encodings of large45;scale source tasks into a small number of parameters and trains an attention module to interpolate the source prompts and a newly initialized target prompt for every instance in the target task. During training only the target task prompt and the attention weights which are shared between tasks in multi45;task training are updated while the original LM and source prompts are intact. ATTEMPT is highly parameter45;efficient (e.g. updates 2300 times fewer parameters than full fine45;tuning) while achieving high task performance using knowledge from high45;resource tasks. Moreover it is modular using pre45;trained soft prompts and can flexibly add or remove source prompts for effective knowledge transfer. Our experimental results across 21 diverse NLP datasets show that ATTEMPT significantly outperforms prompt tuning and outperforms or matches fully fine45;tuned or other parameter45;efficient tuning approaches that use over ten times more parameters. Finally ATTEMPT outperforms previous work in few45;shot learning settings.
