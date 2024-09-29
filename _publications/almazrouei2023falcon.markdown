---
layout: publication
title: "The Falcon Series Of Open Language Models"
authors: Almazrouei Ebtesam, Alobeidli Hamza, Alshamsi Abdulaziz, Cappelli Alessandro, Cojocaru Ruxandra, Debbah Mérouane, Goffinet Étienne, Hesslow Daniel, Launay Julien, Malartic Quentin, Mazzotta Daniele, Noune Badreddine, Pannier Baptiste, Penedo Guilherme
conference: "Arxiv"
year: 2023
bibkey: almazrouei2023falcon
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.16867"}
tags: ['GPT', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
We introduce the Falcon series 7B 40B and 180B parameters causal decoder-only models trained on a diverse high-quality corpora predominantly assembled from web data. The largest model Falcon-180B has been trained on over 3.5 trillion tokens of text--the largest openly documented pretraining run. Falcon-180B significantly outperforms models such as PaLM or Chinchilla and improves upon concurrently developed models such as LLaMA 2 or Inflection-1. It nears the performance of PaLM-2-Large at a reduced pretraining and inference cost making it to our knowledge one of the three best language models in the world along with GPT-4 and PaLM-2-Large. We report detailed evaluations as well as a deep dive into the methods and custom tooling employed to pretrain Falcon. Notably we report on our custom distributed training codebase allowing us to efficiently pretrain these models on up to 4096 A100s on cloud AWS infrastructure with limited interconnect. We release a 600B tokens extract of our web dataset as well as the Falcon-7/40/180B models under a permissive license to foster open-science and accelerate the development of an open ecosystem of large language models.
