---
layout: publication
title: 'Structuredrag: JSON Response Formatting With Large Language Models'
authors: Shorten Connor, Pierse Charles, Smith Thomas Benjamin, Cardenas Erika, Sharma Akanksha, Trengrove John, Van Luijt Bob
conference: "Arxiv"
year: 2024
bibkey: shorten2024json
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11061"}
tags: ['Efficiency And Optimization', 'Prompting', 'Quantization', 'RAG']
---
"The ability of Large Language Models (LLMs) to generate structured outputs, such as JSON, is crucial for their use in Compound AI Systems. However, evaluating and improving this capability remains challenging. In this work, we introduce StructuredRAG, a benchmark of six tasks designed to assess LLMs' proficiency in following response format instructions. We evaluate two state-of-the-art LLMs, Gemini 1.5 Pro and Llama 3 8B-instruct with 4-bit quantization using two distinct prompting strategies. We introduce these prompting strategies as f-String and Follow the Format (FF) prompting. Across 24 experiments, we find an average success rate of 82.55&#37;. We further find a high variance in performance across tasks, models, and prompting strategies with success rates ranging from 0 to 100&#37;. We find that Llama 3 8B-instruct often performs competitively with Gemini 1.5 Pro. We observe that task complexity significantly influences performance, with tasks involving lists or composite object outputs proving more challenging. Our findings highlight the need for further research into improving the reliability and consistency of structured output generation in LLMs. We have open-sourced our experimental code and results at github.com/weaviate/structured-rag."
