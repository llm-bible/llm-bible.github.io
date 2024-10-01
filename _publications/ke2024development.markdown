---
layout: publication
title: 'Development And Testing Of Retrieval Augmented Generation In Large Language Models -- A Case Study Report'
authors: Ke Yuhe, Jin Liyuan, Elangovan Kabilan, Abdullah Hairil Rizal, Liu Nan, Sia Alex Tiong Heng, Soh Chai Rick, Tung Joshua Yi Min, Ong Jasmine Chiat Ling, Ting Daniel Shu Wei
conference: "Arxiv"
year: 2024
bibkey: ke2024development
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01733"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Tools']
---
Purpose: Large Language Models (LLMs) hold significant promise for medical applications. Retrieval Augmented Generation (RAG) emerges as a promising approach for customizing domain knowledge in LLMs. This case study presents the development and evaluation of an LLM-RAG pipeline tailored for healthcare, focusing specifically on preoperative medicine. Methods: We developed an LLM-RAG model using 35 preoperative guidelines and tested it against human-generated responses, with a total of 1260 responses evaluated. The RAG process involved converting clinical documents into text using Python-based frameworks like LangChain and Llamaindex, and processing these texts into chunks for embedding and retrieval. Vector storage techniques and selected embedding models to optimize data retrieval, using Pinecone for vector storage with a dimensionality of 1536 and cosine similarity for loss metrics. Human-generated answers, provided by junior doctors, were used as a comparison. Results: The LLM-RAG model generated answers within an average of 15-20 seconds, significantly faster than the 10 minutes typically required by humans. Among the basic LLMs, GPT4.0 exhibited the best accuracy of 80.1&#37;. This accuracy was further increased to 91.4&#37; when the model was enhanced with RAG. Compared to the human-generated instructions, which had an accuracy of 86.3&#37;, the performance of the GPT4.0 RAG model demonstrated non-inferiority (p=0.610). Conclusions: In this case study, we demonstrated a LLM-RAG model for healthcare implementation. The pipeline shows the advantages of grounded knowledge, upgradability, and scalability as important aspects of healthcare LLM deployment.
