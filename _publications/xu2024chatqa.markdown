---
layout: publication
title: ChatQA 2 Bridging the Gap to Proprietary LLMs in Long Context and RAG Capabilities
authors: Xu Peng, Ping Wei, Wu Xianchao, Xu Chejian, Liu Zihan, Shoeybi Mohammad, Catanzaro Bryan
conference: "Arxiv"
year: 2024
bibkey: xu2024chatqa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.14482"}
tags: ['GPT', 'Applications', 'Arxiv']
---
In this work we introduce ChatQA 2 an Llama 3.0-based model with a 128K context window designed to bridge the gap between open-source LLMs and leading proprietary models (e.g. GPT-4-Turbo) in long-context understanding and retrieval-augmented generation (RAG) capabilities. These two capabilities are essential for LLMs to process large volumes of information that cannot fit into a single prompt and are complementary to each other depending on the downstream tasks and computational budgets. We present a detailed continued training recipe to extend the context window of Llama3-70B-base from 8K to 128K tokens along with a three-stage instruction tuning process to enhance the models instruction-following RAG performance and long-context understanding capabilities. Our results demonstrate that the Llama3-ChatQA-2-70B model outperforms most existing state-of-the-art models including GPT-4-Turbo-2024-04-09 Qwen2-72B-Instruct and Llama3.1-70B-Instruct on ultra-long tasks beyond 100K tokens as well as on the RAG benchmark using only a 4K context window showing the strong long context capability across varying sequence lengths. We further provide extensive comparisons between direct long-context and RAG solutions using the same state-of-the-art long-context LLMs. Interestingly we find that the performance of strong long-context LLMs using RAG improves when retrieving a larger number of chunks. With a large set of top-k chunks RAG consistently outperforms direct long-context solution using the same state-of-the-art long-context models (e.g. Llama3-ChatQA-2-70B and Qwen2-72B-Instruct) on both 32K benchmarks and real-world 128K tasks. To advance research in this field we open-sourced the model weights training data and the evaluation setup for the for the community https://chatqa2-project.github.io/
