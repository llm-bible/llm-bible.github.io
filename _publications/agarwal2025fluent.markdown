---
layout: publication
title: 'Fluent But Culturally Distant: Can Regional Training Teach Cultural Understanding?'
authors: Dhruv Agarwal, Anya Shukla, Sunayana Sitaram, Aditya Vashistha
conference: "Arxiv"
year: 2025
bibkey: agarwal2025fluent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21548"}
tags: ['Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large language models (LLMs) are used around the world but exhibit Western cultural tendencies. To address this cultural misalignment, many countries have begun developing "regional" LLMs tailored to local communities. Yet it remains unclear whether these models merely speak the language of their users or also reflect their cultural values and practices. Using India as a case study, we evaluate five Indic and five global LLMs along two key dimensions: values (via the Inglehart-Welzel map and GlobalOpinionQA) and practices (via CulturalBench and NormAd). Across all four tasks, we find that Indic models do not align more closely with Indian cultural norms than global models. In fact, an average American person is a better proxy for Indian cultural values than any Indic model. Even prompting strategies fail to meaningfully improve alignment. Ablations show that regional fine-tuning does not enhance cultural competence and may in fact hurt it by impeding recall of existing knowledge. We trace this failure to the scarcity of high-quality, untranslated, and culturally grounded pretraining and fine-tuning data. Our study positions cultural evaluation as a first-class requirement alongside multilingual benchmarks and offers a reusable methodology for developers. We call for deeper investments in culturally representative data to build and evaluate truly sovereign LLMs.
