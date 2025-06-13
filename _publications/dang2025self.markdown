---
layout: publication
title: 'SELF: Self-extend The Context Length With Logistic Growth Function'
authors: Phat Thanh Dang, Saahil Thoppay, Wang Yang, Qifan Wang, Vipin Chaudhary, Xiaotian Han
conference: "Arxiv"
year: 2025
bibkey: dang2025self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17296'}
  - {name: "Code", url: 'https://github.com/alexeipc/SELF-LLM'}
tags: ['Attention Mechanism', 'Has Code', 'Training Techniques', 'Applications', 'Model Architecture', 'Prompting']
---
Large language models suffer issues when operated on long contexts that are larger than their training context length due to the standard position encoding for tokens in the attention layer. Tokens a long distance apart will rarely have an effect on each other and long prompts yield unexpected results. To solve this problem, we propose SELF (Self-Extend the Context Length With Logistic Growth Function): a solution of grouping consecutive tokens at varying group sizes using a logistic capacity equation combined with a constant group size at smaller relative distances. Our model had an increase in performance of up to 12% compared to the LongLM extension method in LEval (specifically on the Qwen model). On summarization related tasks in LongBench, our model performed up to 6.4% better than LongLM (specifically on the Llama-2-7b model). On reading comprehension tasks from LEval, our model performed up to 5.4% better than the LongLM. Our code is available at https://github.com/alexeipc/SELF-LLM.
