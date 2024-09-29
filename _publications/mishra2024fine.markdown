---
layout: publication
title: Fine45;grained Hallucination Detection And Editing For Language Models
authors: Mishra Abhika, Asai Akari, Balachandran Vidhisha, Wang Yizhong, Neubig Graham, Tsvetkov Yulia, Hajishirzi Hannaneh
conference: "Arxiv"
year: 2024
bibkey: mishra2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06855"}
tags: ['GPT', 'Model Architecture', 'RAG']
---
Large language models (LMs) are prone to generate factual errors which are often called hallucinations. In this paper we introduce a comprehensive taxonomy of hallucinations and argue that hallucinations manifest in diverse forms each requiring varying degrees of careful assessments to verify factuality. We propose a novel task of automatic fine45;grained hallucination detection and construct a new evaluation benchmark FavaBench that includes about one thousand fine45;grained human judgments on three LM outputs across various domains. Our analysis reveals that ChatGPT and Llama245;Chat (70B 7B) exhibit diverse types of hallucinations in the majority of their outputs in information45;seeking scenarios. We train FAVA a retrieval45;augmented LM by carefully creating synthetic data to detect and correct fine45;grained hallucinations. On our benchmark our automatic and human evaluations show that FAVA significantly outperforms ChatGPT and GPT45;4 on fine45;grained hallucination detection and edits suggested by FAVA improve the factuality of LM45;generated text.
