---
layout: publication
title: Inference45;time Policy Adapters (IPA) Tailoring Extreme45;scale Lms Without Fine45;tuning
authors: Lu Ximing, Brahman Faeze, West Peter, Jang Jaehun, Chandu Khyathi, Ravichander Abhilasha, Qin Lianhui, Ammanabrolu Prithviraj, Jiang Liwei, Ramnath Sahana, Dziri Nouha, Fisher Jillian, Lin Bill Yuchen, Hallinan Skyler, Ren Xiang, Welleck Sean, Choi Yejin
conference: "Arxiv"
year: 2023
bibkey: lu2023inference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15065"}
tags: ['Agentic', 'Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
While extreme45;scale language models have demonstrated exceptional performance on a variety of language tasks the degree of control over these language models through pure prompting can often be limited. Directly fine45;tuning such language models can be effective for tailoring them but it can be either extremely costly (e.g. GPT45;3) or not even feasible for the broader community (e.g. GPT45;4). We propose Inference45;time Policy Adapters (IPA) which efficiently tailors a language model such as GPT45;3 without fine45;tuning it. IPA guides a large base model during decoding time through a lightweight policy adapter trained to optimize an arbitrary user objective with reinforcement learning. On five challenging text generation tasks such as toxicity reduction and lexically constrained generation IPA consistently brings significant improvements over off45;the45;shelf language models. It outperforms competitive baseline methods sometimes even including expensive fine45;tuning. In particular tailoring GPT45;2 with IPA can outperform GPT45;3 while tailoring GPT45;3 with IPA brings a major performance boost over GPT45;3 (and sometimes even over GPT45;4). Our promising results highlight the potential of IPA as a lightweight alternative to tailoring extreme45;scale language models.
