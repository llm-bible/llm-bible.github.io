---
layout: publication
title: Comparing Plausibility Estimates in Base and Instruction-Tuned Large Language Models
authors: Kauf Carina, Chersoni Emmanuele, Lenci Alessandro, Fedorenko Evelina, Ivanova Anna A.
conference: "Arxiv"
year: 2024
bibkey: kauf2024comparing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14859"}
tags: ['Model Architecture', 'Prompting', 'Survey Paper', 'Training Techniques']
---
Instruction-tuned LLMs can respond to explicit queries formulated as prompts which greatly facilitates interaction with human users. However prompt-based approaches might not always be able to tap into the wealth of implicit knowledge acquired by LLMs during pre-training. This paper presents a comprehensive study of ways to evaluate semantic plausibility in LLMs. We compare base and instruction-tuned LLM performance on an English sentence plausibility task via (a) explicit prompting and (b) implicit estimation via direct readout of the probabilities models assign to strings. Experiment 1 shows that across model architectures and plausibility datasets (i) log likelihood () scores are the most reliable indicator of sentence plausibility with zero-shot prompting yielding inconsistent and typically poor results; (ii) -based performance is still inferior to human performance; (iii) instruction-tuned models have worse -based performance than base models. In Experiment 2 we show that scores across models are modulated by context in the expected way showing high performance on three metrics of context-sensitive plausibility and providing a direct match to explicit human plausibility judgments. Overall estimates remain a more reliable measure of plausibility in LLMs than direct prompting.
