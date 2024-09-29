---
layout: publication
title: Identifying Query45;relevant Neurons In Large Language Models For Long45;form Texts
authors: Chen Lihu, Dejl Adam, Toni Francesca
conference: "Arxiv"
year: 2024
bibkey: chen2024identifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10868"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) possess vast amounts of knowledge within their parameters prompting research into methods for locating and editing this knowledge. Previous work has largely focused on locating entity45;related (often single45;token) facts in smaller models. However several key questions remain unanswered (1) How can we effectively locate query45;relevant neurons in contemporary autoregressive LLMs such as Llama and Mistral (2) How can we address the challenge of long45;form text generation (3) Are there localized knowledge regions in LLMs In this study we introduce Query45;Relevant Neuron Cluster Attribution (QRNCA) a novel architecture45;agnostic framework capable of identifying query45;relevant neurons in LLMs. QRNCA allows for the examination of long45;form answers beyond triplet facts by employing the proxy task of multi45;choice question answering. To evaluate the effectiveness of our detected neurons we build two multi45;choice QA datasets spanning diverse domains and languages. Empirical evaluations demonstrate that our method outperforms baseline methods significantly. Further analysis of neuron distributions reveals the presence of visible localized regions particularly within different domains. Finally we show potential applications of our detected neurons in knowledge editing and neuron45;based prediction.
