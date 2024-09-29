---
layout: publication
title: Chatqa Surpassing GPT45;4 On Conversational QA And RAG
authors: Liu Zihan, Ping Wei, Roy Rajarshi, Xu Peng, Lee Chankyu, Shoeybi Mohammad, Catanzaro Bryan
conference: "Arxiv"
year: 2024
bibkey: liu2024surpassing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10225"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG']
---
In this work we introduce ChatQA a suite of models that outperform GPT45;4 on retrieval45;augmented generation (RAG) and conversational question answering (QA). To enhance generation we propose a two45;stage instruction tuning method that significantly boosts the performance of RAG. For effective retrieval we introduce a dense retriever optimized for conversational QA which yields results comparable to the alternative state45;of45;the45;art query rewriting models while substantially reducing deployment costs. We also present the ChatRAG Bench which encompasses ten datasets covering comprehensive evaluations on RAG table45;related QA arithmetic calculations and scenarios involving unanswerable questions. Our ChatQA45;1.045;70B (score 54.14) built on Llama2 a weaker foundation model than GPT45;4 can slightly outperform GPT45;445;0613 (score 53.90) and GPT45;445;Turbo45;202445;0445;09 (score 54.03) on the ChatRAG Bench without relying on any synthetic data from OpenAI GPT models. Notably the Llama345;ChatQA45;1.545;70B model surpasses the accuracy of GPT45;445;Turbo45;202445;0445;09 achieving a 4.437; improvement. To advance research in this field we open45;sourced the model weights instruction tuning data ChatRAG Bench and retriever for the community https://chatqa&#45;project.github.io/.
