---
layout: publication
title: Lever LM Configuring In45;context Sequence To Lever Large Vision Language Models
authors: Yang Xu, Peng Yingzhe, Ma Haoxuan, Xu Shuo, Zhang Chi, Han Yucheng, Zhang Hanwang
conference: "Arxiv"
year: 2023
bibkey: yang2023lever
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10104"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
As Archimedes famously said Give me a lever long enough and a fulcrum on which to place it and I shall move the world in this study we propose to use a tiny Language Model (LM) eg a Transformer with 67M parameters to lever much larger Vision45;Language Models (LVLMs) with 9B parameters. Specifically we use this tiny textbf123;Lever45;LM125; to configure effective in45;context demonstration (ICD) sequences to improve the In45;Context Learinng (ICL) performance of LVLMs. Previous studies show that diverse ICD configurations like the selection and ordering of the demonstrations heavily affect the ICL performance highlighting the significance of configuring effective ICD sequences. Motivated by this and by re45;considering the the process of configuring ICD sequence we find this is a mirror process of human sentence composition and further assume that effective ICD configurations may contain internal statistical patterns that can be captured by Lever45;LM. Then a dataset with effective ICD sequences is constructed to train Lever45;LM. After training given novel queries new ICD sequences are configured by the trained Lever45;LM to solve vision45;language tasks through ICL. Experiments show that these ICD sequences can improve the ICL performance of two LVLMs compared with some strong baselines in Visual Question Answering and Image Captioning validating that Lever45;LM can really capture the statistical patterns for levering LVLMs.
