---
layout: publication
title: Generating Query Recommendations via LLMs
authors: Bacciu Andrea, Palumbo Enrico, Damianou Andreas, Tonellotto Nicola, Silvestri Fabrizio
conference: "Arxiv"
year: 2024
bibkey: bacciu2024generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19749"}
tags: ['ARXIV', 'Applications', 'LLM', 'Prompt', 'Tools']
---
Query recommendation systems are ubiquitous in modern search engines assisting users in producing effective queries to meet their information needs. However these systems require a large amount of data to produce good recommendations such as a large collection of documents to index and query logs. In particular query logs and user data are not available in cold start scenarios. Query logs are expensive to collect and maintain and require complex and time-consuming cascading pipelines for creating combining and ranking recommendations. To address these issues we frame the query recommendation problem as a generative task proposing a novel approach called Generative Query Recommendation (GQR). GQR uses an LLM as its foundation and does not require to be trained or fine-tuned to tackle the query recommendation problem. We design a prompt that enables the LLM to understand the specific recommendation task even using a single example. We then improved our system by proposing a version that exploits query logs called Retriever-Augmented GQR (RA-GQR). RA-GQr dynamically composes its prompt by retrieving similar queries from query logs. GQR approaches reuses a pre-existing neural architecture resulting in a simpler and more ready-to-market approach even in a cold start scenario. Our proposed GQR obtains state-of-the-art performance in terms of NDCG@10 and clarity score against two commercial search engines and the previous state-of-the-art approach on the Robust04 and ClueWeb09B collections improving on average the NDCG@10 performance up to ~4 on Robust04 and ClueWeb09B w.r.t the previous best competitor. RA-GQR further improve the NDCG@10 obtaining an increase of ~11 ~6 on Robust04 and ClueWeb09B w.r.t the best competitor. Furthermore our system obtained ~59 of user preferences in a blind user study proving that our method produces the most engaging queries.
