---
layout: publication
title: Llms45;as45;instructors Learning From Errors Toward Automating Model Improvement
authors: Ying Jiahao, Lin Mingbao, Cao Yixin, Tang Wei, Wang Bo, Sun Qianru, Huang Xuanjing, Yan Shuicheng
conference: "Arxiv"
year: 2024
bibkey: ying2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00497"}
  - {name: "Code", url: "https://yingjiahao14.github.io/LLMs&#45;as&#45;Instructors&#45;pages/"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
This paper introduces the innovative LLMs45;as45;Instructors framework which leverages the advanced Large Language Models (LLMs) to autonomously enhance the training of smaller target models. Inspired by the theory of Learning from Errors this framework employs an instructor LLM to meticulously analyze the specific errors within a target model facilitating targeted and efficient training cycles. Within this framework we implement two strategies Learning from Error which focuses solely on incorrect responses to tailor training data and Learning from Error by Contrast which uses contrastive learning to analyze both correct and incorrect responses for a deeper understanding of errors. Our empirical studies conducted with several open45;source models demonstrate significant improvements across multiple benchmarks including mathematical reasoning coding abilities and factual knowledge. Notably the refined Llama45;345;8b45;Instruction has outperformed ChatGPT illustrating the effectiveness of our approach. By leveraging the strengths of both strategies we have attained a more balanced performance improvement on both in45;domain and out45;of45;domain benchmarks. Our code can be found at https://yingjiahao14.github.io/LLMs&#45;as&#45;Instructors&#45;pages/.
