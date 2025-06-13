---
layout: publication
title: 'TALKPLAY: Multimodal Music Recommendation With Large Language Models'
authors: Seungheon Doh, Keunwoo Choi, Juhan Nam
conference: "Arxiv"
year: 2025
bibkey: doh2025multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13713"}
tags: ['RAG', 'Model Architecture', 'Multimodal Models']
---
We present TALKPLAY, a novel multimodal music recommendation system that reformulates recommendation as a token generation problem using large language models (LLMs). By leveraging the instruction-following and natural language generation capabilities of LLMs, our system effectively recommends music from diverse user queries while generating contextually relevant responses. While pretrained LLMs are primarily designed for text modality, TALKPLAY extends their scope through two key innovations: a multimodal music tokenizer that encodes audio features, lyrics, metadata, semantic tags, and playlist co-occurrence signals; and a vocabulary expansion mechanism that enables unified processing and generation of both linguistic and music-relevant tokens. By integrating the recommendation system directly into the LLM architecture, TALKPLAY transforms conventional systems by: (1) unifying previous two-stage conversational recommendation systems (recommendation engines and dialogue managers) into a cohesive end-to-end system, (2) effectively utilizing long conversational context for recommendation while maintaining strong performance in extended multi-turn interactions, and (3) generating natural language responses for seamless user interaction. Our qualitative and quantitative evaluation demonstrates that TALKPLAY significantly outperforms unimodal approaches based solely on text or listening history in both recommendation performance and conversational naturalness.
