---
layout: publication
title: Fingpt&#58; Large Generative Models For A Small Language
authors: Luukkonen Risto, Komulainen Ville, Luoma Jouni, Eskelinen Anni, Kanerva Jenna, Kupari Hanna-mari, Ginter Filip, Laippala Veronika, Muennighoff Niklas, Piktus Aleksandra, Wang Thomas, Tazi Nouamane, Scao Teven Le, Wolf Thomas, Suominen Osma, Sairanen Samuli, Merioksa Mikko, Heinonen Jyrki, Vahtola Aija, Antao Samuel, Pyysalo Sampo
conference: "Arxiv"
year: 2023
bibkey: luukkonen2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.05640"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) excel in many tasks in NLP and beyond but most open models have very limited coverage of smaller languages and LLM work tends to focus on languages where nearly unlimited data is available for pretraining. In this work we study the challenges of creating LLMs for Finnish a language spoken by less than 0.137; of the world population. We compile an extensive dataset of Finnish combining web crawls news social media and eBooks. We pursue two approaches to pretrain models 1) we train seven monolingual models from scratch (186M to 13B parameters) dubbed FinGPT 2) we continue the pretraining of the multilingual BLOOM model on a mix of its original training data and Finnish resulting in a 176 billion parameter model we call BLUUMI. For model evaluation we introduce FIN-bench a version of BIG-bench with Finnish tasks. We also assess other model qualities such as toxicity and bias. Our models and tools are openly available at https://turkunlp.org/gpt3-finnish."
