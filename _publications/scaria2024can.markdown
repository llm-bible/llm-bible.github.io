---
layout: publication
title: 'Can Small Language Models Learn, Unlearn, And Retain Noise Patterns?'
authors: Nicy Scaria, Silvester John Joseph Kennedy, Deepak Subramani
conference: "Arxiv"
year: 2024
bibkey: scaria2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00996"}
tags: ['Pretraining Methods', 'Training Techniques', 'Applications', 'Reinforcement Learning']
---
With the growing need for efficient language models in resource-constrained environments, Small Language Models (SLMs) have emerged as compact and practical alternatives to Large Language Models (LLMs). While studies have explored noise handling in LLMs, little is known about how SLMs handle noise, a critical factor for their reliable real-world deployment. This study investigates the ability of SLMs with parameters between 1 and 3 billion to learn, retain, and subsequently eliminate different types of noise (word flip, character flip, transliteration, irrelevant content, and contradictory information). Four pretrained SLMs (Olmo 1B, Qwen1.5 1.8B, Gemma1.1 2B, and Phi2 2.7B) were instruction-tuned on noise-free data and tested with in-context examples to assess noise learning. Subsequently, noise patterns were introduced in instruction tuning to assess their adaptability. The results revealed differences in how models handle noise, with smaller models like Olmo quickly adapting to noise patterns. Phi2's carefully curated, structured, and high-quality pretraining data enabled resistance to character level, transliteration, and counterfactual noise, while Gemma adapted successfully to transliteration noise through its multilingual pretraining. Subsequent clean data training effectively mitigated noise effects. These findings provide practical strategies for developing robust SLMs for real-world applications.
