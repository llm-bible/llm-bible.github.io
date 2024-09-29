---
layout: publication
title: Superposition Prompting\: Improving And Accelerating Retrieval-augmented Generation
authors: Merth Thomas, Fu Qichen, Rastegari Mohammad, Najibi Mahyar
conference: "Arxiv"
year: 2024
bibkey: merth2024superposition
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06910"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Despite the successes of large language models (LLMs) they exhibit significant drawbacks particularly when processing long contexts. Their inference cost scales quadratically with respect to sequence length making it expensive for deployment in some real-world text processing applications such as retrieval-augmented generation (RAG). Additionally LLMs also exhibit the distraction phenomenon where irrelevant context in the prompt degrades output quality. To address these drawbacks we propose a novel RAG prompting methodology superposition prompting which can be directly applied to pre-trained transformer-based LLMs without the need for fine-tuning. At a high level superposition prompting allows the LLM to process input documents in parallel prompt paths discarding paths once they are deemed irrelevant. We demonstrate the capability of our method to simultaneously enhance time efficiency across a variety of question-answering benchmarks using multiple pre-trained LLMs. Furthermore our technique significantly improves accuracy when the retrieved context is large relative the context the model was trained on. For example our approach facilitates a 93x reduction in compute time while improving accuracy by 4337; on the NaturalQuestions-Open dataset with the MPT-7B instruction-tuned model over naive RAG.
