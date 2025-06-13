---
layout: publication
title: 'Tower: An Open Multilingual Large Language Model For Translation-related Tasks'
authors: Duarte M. Alves, José Pombal, Nuno M. Guerreiro, Pedro H. Martins, João Alves, Amin Farajian, Ben Peters, Ricardo Rei, Patrick Fernandes, Sweta Agrawal, Pierre Colombo, José G. C. De Souza, André F. T. Martins
conference: "Arxiv"
year: 2024
bibkey: alves2024open
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.17733'}
tags: ['Training Techniques', 'Tools', 'Pretraining Methods']
---
While general-purpose large language models (LLMs) demonstrate proficiency on
multiple tasks within the domain of translation, approaches based on open LLMs
are competitive only when specializing on a single task. In this paper, we
propose a recipe for tailoring LLMs to multiple tasks present in translation
workflows. We perform continued pretraining on a multilingual mixture of
monolingual and parallel data, creating TowerBase, followed by finetuning on
instructions relevant for translation processes, creating TowerInstruct. Our
final model surpasses open alternatives on several tasks relevant to
translation workflows and is competitive with general-purpose closed LLMs. To
facilitate future research, we release the Tower models, our specialization
dataset, an evaluation framework for LLMs focusing on the translation
ecosystem, and a collection of model generations, including ours, on our
benchmark.
