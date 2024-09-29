---
layout: publication
title: Deciphering The Factors Influencing The Efficacy Of Chain-of-thought\: Probability, Memorization, And Noisy Reasoning
authors: Prabhakar Akshara, Griffiths Thomas L., Mccoy R. Thomas
conference: "Arxiv"
year: 2024
bibkey: prabhakar2024deciphering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01687"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Chain-of-Thought (CoT) prompting has been shown to enhance the multi-step reasoning capabilities of Large Language Models (LLMs). However debates persist about whether LLMs exhibit abstract generalization or rely on shallow heuristics when given CoT prompts. To understand the factors influencing CoT reasoning we provide a detailed case study of the symbolic reasoning task of decoding shift ciphers where letters are shifted forward some number of steps in the alphabet. GPT-4 achieves zero accuracy on most shift ciphers with standard prompting but with CoT its accuracy improves to an average of 3237;. By focusing on a single relatively simple task we are able to identify three factors that systematically affect CoT performance the probability of the tasks expected output (probability) what the model has implicitly learned during pre-training (memorization) and the number of intermediate operations involved in reasoning (noisy reasoning). We show that these factors can drastically influence the task accuracy; e.g. varying the outputs probability of occurrence can shift accuracy from 2637; to 7037;. We also demonstrate that it is essential for the model to explicitly produce intermediate steps as output that can be conditioned on to increase the probability of the correct answer. Our experiments indicate that as long as the model does so the validity of the demonstrations in the prompt does not matter. Overall we conclude that CoT prompting performance reflects both memorization and a probabilistic version of genuine reasoning.
