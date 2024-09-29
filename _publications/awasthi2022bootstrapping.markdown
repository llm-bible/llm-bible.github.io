---
layout: publication
title: Bootstrapping Multilingual Semantic Parsers Using Large Language Models
authors: Awasthi Abhijeet, Gupta Nitish, Samanta Bidisha, Dave Shachi, Sarawagi Sunita, Talukdar Partha
conference: "Arxiv"
year: 2022
bibkey: awasthi2022bootstrapping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.07313"}
tags: ['Few Shot', 'In Context Learning', 'Prompting', 'Training Techniques']
---
Despite cross-lingual generalization demonstrated by pre-trained multilingual models the translate-train paradigm of transferring English datasets across multiple languages remains to be a key mechanism for training task-specific multilingual models. However for many low-resource languages the availability of a reliable translation service entails significant amounts of costly human-annotated translation pairs. Further translation services may continue to be brittle due to domain mismatch between task-specific input text and general-purpose text used for training translation models. For multilingual semantic parsing we demonstrate the effectiveness and flexibility offered by large language models (LLMs) for translating English datasets into several languages via few-shot prompting. Through extensive comparisons on two public datasets MTOP and MASSIVE spanning 50 languages and several domains we show that our method of translating data using LLMs outperforms a strong translate-train baseline on 41 out of 50 languages. We study the key design choices that enable more effective multilingual data translation via prompted LLMs.
