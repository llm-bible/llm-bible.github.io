---
layout: publication
title: 'Auto-cypher: Improving Llms On Cypher Generation Via Llm-supervised Generation-verification Framework'
authors: Aman Tiwari, Shiva Krishna Reddy Malay, Vikas Yadav, Masoud Hashemi, Sathwik Tejaswi Madhusudhan
conference: "Arxiv"
year: 2024
bibkey: tiwari2024auto
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12612'}
tags: ['Tools', 'Training Techniques']
---
Graph databases like Neo4j are gaining popularity for handling complex,
interconnected data, over traditional relational databases in modeling and
querying relationships. While translating natural language into SQL queries is
well-researched, generating Cypher queries for Neo4j remains relatively
underexplored. In this work, we present an automated, LLM-Supervised, pipeline
to generate high-quality synthetic data for Text2Cypher. Our Cypher data
generation pipeline introduces LLM-As-Database-Filler, a novel strategy for
ensuring Cypher query correctness, thus resulting in high quality generations.
Using our pipeline, we generate high quality Text2Cypher data - SynthCypher
containing 29.8k instances across various domains and queries with varying
complexities. Training open-source LLMs like LLaMa-3.1-8B, Mistral-7B, and
QWEN-7B on SynthCypher results in performance gains of up to 40% on the
Text2Cypher test split and 30% on the SPIDER benchmark, adapted for graph
databases.
