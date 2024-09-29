---
layout: publication
title: Making Large Language Models Interactive&#58; A Pioneer Study On Supporting Complex Information-seeking Tasks With Implicit Constraints
authors: Ahmadvand Ali, Arabzadeh Negar, Kiseleva Julia, Sanz Patricio Figueroa, Deng Xin, Jauhar Sujay, Gamon Michael, Agichtein Eugene, Friend Ned, Aniruddha
conference: "Arxiv"
year: 2022
bibkey: ahmadvand2022making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.00584"}
tags: ['Agentic', 'Fine Tuning', 'RAG', 'Reinforcement Learning', 'Tools']
---
Current interactive systems with natural language interfaces lack the ability to understand a complex information-seeking request which expresses several implicit constraints at once and there is no prior information about user preferences e.g.find hiking trails around San Francisco which are accessible with toddlers and have beautiful scenery in summer where output is a list of possible suggestions for users to start their exploration. In such scenarios user requests can be issued in one shot in the form of a complex and long query unlike conversational and exploratory search models where require short utterances or queries are often presented to the system step by step. We have designed and deployed a platform to collect the data from approaching such complex interactive systems. Moreover despite with the current advancement of generative language models these models suffer from hallucination in providing accurate factual knowledge. All language models are mostly trained in large part on web-scraped data from the past which usually is not useful for immediate users needs. In this article we propose an IA that leverages Large Language Models (LLM) for complex request understanding and makes it interactive using Reinforcement learning that allows intricately refine user requests by making them complete leading to better retrieval and reduce LLMs hallucination problems for current user needs. To demonstrate the performance of the proposed modeling paradigm we have adopted various pre-retrieval metrics that capture the extent to which guided interactions with our system yield better retrieval results. Through extensive experimentation we demonstrated that our method significantly outperforms several robust baselines.
