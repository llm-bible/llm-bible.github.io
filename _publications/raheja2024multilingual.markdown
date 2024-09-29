---
layout: publication
title: Medit Multilingual Text Editing Via Instruction Tuning
authors: Raheja Vipul, Alikaniotis Dimitris, Kulkarni Vivek, Alhafni Bashar, Kumar Dhruv
conference: "Arxiv"
year: 2024
bibkey: raheja2024multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16472"}
  - {name: "Code", url: "https://github.com/vipulraheja/medit"}
tags: ['Has Code', 'Pretraining Methods', 'Training Techniques']
---
We introduce mEdIT a multi45;lingual extension to CoEdIT 45;45; the recent state45;of45;the45;art text editing models for writing assistance. mEdIT models are trained by fine45;tuning multi45;lingual large pre45;trained language models (LLMs) via instruction tuning. They are designed to take instructions from the user specifying the attributes of the desired text in the form of natural language instructions such as Grammatik korrigieren (German) or Parafrasee la oracion (Spanish). We build mEdIT by curating data from multiple publicly available human45;annotated text editing datasets for three text editing tasks (Grammatical Error Correction (GEC) Text Simplification and Paraphrasing) across diverse languages belonging to six different language families. We detail the design and training of mEdIT models and demonstrate their strong performance on many multi45;lingual text editing benchmarks against other multilingual LLMs. We also find that mEdIT generalizes effectively to new languages over multilingual baselines. We publicly release our data code and trained models at https://github.com/vipulraheja/medit.
