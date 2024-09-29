---
layout: publication
title: Chatqa 2 Bridging The Gap To Proprietary Llms In Long Context And RAG Capabilities
authors: Xu Peng, Ping Wei, Wu Xianchao, Xu Chejian, Liu Zihan, Shoeybi Mohammad, Catanzaro Bryan
conference: "Arxiv"
year: 2024
bibkey: xu2024chatqa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.14482"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
In this work we introduce ChatQA 2 an Llama 3.045;based model with a 128K context window designed to bridge the gap between open45;source LLMs and leading proprietary models (e.g. GPT45;445;Turbo) in long45;context understanding and retrieval45;augmented generation (RAG) capabilities. These two capabilities are essential for LLMs to process large volumes of information that cannot fit into a single prompt and are complementary to each other depending on the downstream tasks and computational budgets. We present a detailed continued training recipe to extend the context window of Llama345;70B45;base from 8K to 128K tokens along with a three45;stage instruction tuning process to enhance the models instruction45;following RAG performance and long45;context understanding capabilities. Our results demonstrate that the Llama345;ChatQA45;245;70B model outperforms most existing state45;of45;the45;art models including GPT45;445;Turbo45;202445;0445;09 Qwen245;72B45;Instruct and Llama3.145;70B45;Instruct on ultra45;long tasks beyond 100K tokens as well as on the RAG benchmark using only a 4K context window showing the strong long context capability across varying sequence lengths. We further provide extensive comparisons between direct long45;context and RAG solutions using the same state45;of45;the45;art long45;context LLMs. Interestingly we find that the performance of strong long45;context LLMs using RAG improves when retrieving a larger number of chunks. With a large set of top45;k chunks RAG consistently outperforms direct long45;context solution using the same state45;of45;the45;art long45;context models (e.g. Llama345;ChatQA45;245;70B and Qwen245;72B45;Instruct) on both 32K benchmarks and real45;world 128K tasks. To advance research in this field we open45;sourced the model weights training data and the evaluation setup for the for the community https://chatqa2&#45;project.github.io/
