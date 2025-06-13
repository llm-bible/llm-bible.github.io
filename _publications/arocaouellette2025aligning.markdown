---
layout: publication
title: 'Aligning Llms By Predicting Preferences From User Writing Samples'
authors: Stéphane Aroca-ouellette, Natalie Mackraz, Barry-john Theobald, Katherine Metcalf
conference: "Arxiv"
year: 2025
bibkey: arocaouellette2025aligning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23815'}
tags: ['Agentic', 'Model Architecture', 'Applications', 'GPT']
---
Accommodating human preferences is essential for creating aligned LLM agents that deliver personalized and effective interactions. Recent work has shown the potential for LLMs acting as writing agents to infer a description of user preferences. Agent alignment then comes from conditioning on the inferred preference description. However, existing methods often produce generic preference descriptions that fail to capture the unique and individualized nature of human preferences. This paper introduces PROSE, a method designed to enhance the precision of preference descriptions inferred from user writing samples. PROSE incorporates two key elements: (1) iterative refinement of inferred preferences, and (2) verification of inferred preferences across multiple user writing samples. We evaluate PROSE with several LLMs (i.e., Qwen2.5 7B and 72B Instruct, GPT-mini, and GPT-4o) on a summarization and an email writing task. We find that PROSE more accurately infers nuanced human preferences, improving the quality of the writing agent's generations over CIPHER (a state-of-the-art method for inferring preferences) by 33%. Lastly, we demonstrate that ICL and PROSE are complementary methods, and combining them provides up to a 9% improvement over ICL alone.
