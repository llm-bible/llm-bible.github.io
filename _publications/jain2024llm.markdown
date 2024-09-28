---
layout: publication
title: LLM Agents Improve Semantic Code Search
authors: Jain Sarthak University Of Illinois Urbana Champaign And Cisco, Dora Aditya University Of Illinois Urbana Champaign, Sam Ka Seng University Of Illinois Urbana Champaign, Singh Prabhat Cisco
conference: "Arxiv"
year: 2024
bibkey: jain2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11058"}
tags: ['ARXIV', 'Agent', 'LLM', 'Multimodal Models', 'Prompt', 'RAG', 'Tools']
---
Code Search is a key task that many programmers often have to perform while developing solutions to problems. Current methodologies suffer from an inability to perform accurately on prompts that contain some ambiguity or ones that require additional context relative to a code-base. We introduce the approach of using Retrieval Augmented Generation (RAG) powered agents to inject information into user prompts allowing for better inputs into embedding models. By utilizing RAG agents enhance user queries with relevant details from GitHub repositories making them more informative and contextually aligned. Additionally we introduce a multi-stream ensemble approach which when paired with agentic workflow can obtain improved retrieval accuracy which we deploy on application called repo-rift.com. Experimental results on the CodeSearchNet dataset demonstrate that RepoRift significantly outperforms existing methods achieving an 78.2 success rate at Success@10 and a 34.6 success rate at Success@1. This research presents a substantial advancement in semantic code search highlighting the potential of agentic LLMs and RAG to enhance code retrieval systems.
