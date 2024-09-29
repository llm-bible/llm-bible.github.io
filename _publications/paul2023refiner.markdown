---
layout: publication
title: REFINER Reasoning Feedback on Intermediate Representations
authors: Paul Debjit, Ismayilzada Mete, Peyrard Maxime, Borges Beatriz, Bosselut Antoine, West Robert, Faltings Boi
conference: "Arxiv"
year: 2023
bibkey: paul2023refiner
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.01904"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools']
---
Language models (LMs) have recently shown remarkable performance on reasoning tasks by explicitly generating intermediate inferences e.g. chain-of-thought prompting. However these intermediate inference steps may be inappropriate deductions from the initial context and lead to incorrect final predictions. Here we introduce REFINER a framework for finetuning LMs to explicitly generate intermediate reasoning steps while interacting with a critic model that provides automated feedback on the reasoning. Specifically the critic provides structured feedback that the reasoning LM uses to iteratively improve its intermediate arguments. Empirical evaluations of REFINER on three diverse reasoning tasks show significant improvements over baseline LMs of comparable scale. Furthermore when using GPT-3.5 or ChatGPT as the reasoner the trained critic significantly improves reasoning without finetuning the reasoner. Finally our critic model is trained without expensive human-in-the-loop data but can be substituted with humans at inference time.
