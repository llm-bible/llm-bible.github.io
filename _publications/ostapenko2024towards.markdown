---
layout: publication
title: 'Towards Modular Llms By Building And Reusing A Library Of Loras'
authors: Ostapenko Oleksiy, Su Zhan, Ponti Edoardo Maria, Charlin Laurent, Roux Nicolas Le, Pereira Matheus, Caccia Lucas, Sordoni Alessandro
conference: "Arxiv"
year: 2024
bibkey: ostapenko2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11157"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
The growing number of parameter-efficient adaptations of a base large language model (LLM) calls for studying whether we can reuse such trained adapters to improve performance for new tasks. We study how to best build a library of adapters given multi-task data and devise techniques for both zero-shot and supervised task generalization through routing in such library. We benchmark existing approaches to build this library and introduce model-based clustering, MBC, a method that groups tasks based on the similarity of their adapter parameters, indirectly optimizing for transfer across the multi-task dataset. To re-use the library, we present a novel zero-shot routing mechanism, Arrow, which enables dynamic selection of the most relevant adapters for new inputs without the need for retraining. We experiment with several LLMs, such as Phi-2 and Mistral, on a wide array of held-out tasks, verifying that MBC-based adapters and Arrow routing lead to superior generalization to new tasks. We make steps towards creating modular, adaptable LLMs that can match or outperform traditional joint training.
