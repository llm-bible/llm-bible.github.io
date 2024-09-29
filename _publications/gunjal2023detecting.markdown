---
layout: publication
title: Detecting And Preventing Hallucinations In Large Vision Language Models
authors: Anisha Gunjal, Jihan Yin, Erhan Bas
conference: "Arxiv"
year: 2023
bibkey: gunjal2023detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2308.06394v3"}
tags: ['Applications', 'Efficiency And Optimization', 'Reinforcement Learning']
---
Instruction tuned Large Vision Language Models (LVLMs) have significantly advanced in generalizing across a diverse set of multi45;modal tasks especially for Visual Question Answering (VQA). However generating detailed responses that are visually grounded is still a challenging task for these models. We find that even the current state45;of45;the45;art LVLMs (InstructBLIP) still contain a staggering 30 percent of the hallucinatory text in the form of non45;existent objects unfaithful descriptions and inaccurate relationships. To address this we introduce M45;HalDetect a (M)ultimodal (Hal)lucination (Detect)ion Dataset that can be used to train and benchmark models for hallucination detection and prevention. M45;HalDetect consists of 16k fine45;grained annotations on VQA examples making it the first comprehensive multi45;modal hallucination detection dataset for detailed image descriptions. Unlike previous work that only consider object hallucination we additionally annotate both entity descriptions and relationships that are unfaithful. To demonstrate the potential of this dataset for hallucination prevention we optimize InstructBLIP through our novel Fine45;grained Direct Preference Optimization (FDPO). We also train fine45;grained multi45;modal reward models from InstructBLIP and evaluate their effectiveness with best45;of45;n rejection sampling. We perform human evaluation on both FDPO and rejection sampling and find that they reduce hallucination rates in InstructBLIP by 4137; and 5537; respectively. We also find that our reward model generalizes to other multi45;modal models reducing hallucinations in LLaVA and mPLUG45;OWL by 1537; and 5737; respectively and has strong correlation with human evaluated accuracy scores.
