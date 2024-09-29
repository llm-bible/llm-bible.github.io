---
layout: publication
title: Generating Query Recommendations Via Llms
authors: Bacciu Andrea, Palumbo Enrico, Damianou Andreas, Tonellotto Nicola, Silvestri Fabrizio
conference: "Arxiv"
year: 2024
bibkey: bacciu2024generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19749"}
tags: ['Model Architecture', 'Prompting', 'RAG']
---
Query recommendation systems are ubiquitous in modern search engines assisting users in producing effective queries to meet their information needs. However these systems require a large amount of data to produce good recommendations such as a large collection of documents to index and query logs. In particular query logs and user data are not available in cold start scenarios. Query logs are expensive to collect and maintain and require complex and time45;consuming cascading pipelines for creating combining and ranking recommendations. To address these issues we frame the query recommendation problem as a generative task proposing a novel approach called Generative Query Recommendation (GQR). GQR uses an LLM as its foundation and does not require to be trained or fine45;tuned to tackle the query recommendation problem. We design a prompt that enables the LLM to understand the specific recommendation task even using a single example. We then improved our system by proposing a version that exploits query logs called Retriever45;Augmented GQR (RA45;GQR). RA45;GQr dynamically composes its prompt by retrieving similar queries from query logs. GQR approaches reuses a pre45;existing neural architecture resulting in a simpler and more ready45;to45;market approach even in a cold start scenario. Our proposed GQR obtains state45;of45;the45;art performance in terms of NDCG35;64;10 and clarity score against two commercial search engines and the previous state45;of45;the45;art approach on the Robust04 and ClueWeb09B collections improving on average the NDCG35;64;10 performance up to ~437; on Robust04 and ClueWeb09B w.r.t the previous best competitor. RA45;GQR further improve the NDCG35;64;10 obtaining an increase of ~1137; ~637; on Robust04 and ClueWeb09B w.r.t the best competitor. Furthermore our system obtained ~5937; of user preferences in a blind user study proving that our method produces the most engaging queries.
