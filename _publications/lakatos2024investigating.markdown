---
layout: publication
title: 'Investigating The Performance Of Retrieval-augmented Generation And Fine-tuning For The Development Of Ai-driven Knowledge-based Systems'
authors: Robert Lakatos, Peter Pollner, Andras Hajdu, Tamas Joo
conference: "Mach. Learn. Knowl. Extr. 2025 7 15"
year: 2024
bibkey: lakatos2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09727"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
The development of generative large language models (G-LLM) opened up new opportunities for the development of new types of knowledge-based systems similar to ChatGPT, Bing, or Gemini. Fine-tuning (FN) and Retrieval-Augmented Generation (RAG) are the techniques that can be used to implement domain adaptation for the development of G-LLM-based knowledge systems. In our study, using ROUGE, BLEU, METEOR scores, and cosine similarity, we compare and examine the performance of RAG and FN for the GPT-J-6B, OPT-6.7B, LlaMA, LlaMA-2 language models. Based on measurements shown on different datasets, we demonstrate that RAG-based constructions are more efficient than models produced with FN. We point out that connecting RAG and FN is not trivial, because connecting FN models with RAG can cause a decrease in performance. Furthermore, we outline a simple RAG-based architecture which, on average, outperforms the FN models by 16% in terms of the ROGUE score, 15% in the case of the BLEU score, and 53% based on the cosine similarity. This shows the significant advantage of RAG over FN in terms of hallucination, which is not offset by the fact that the average 8% better METEOR score of FN models indicates greater creativity compared to RAG.
