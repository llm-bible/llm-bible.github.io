---
layout: publication
title: 'Evaluating Large Language Models For Code Review'
authors: Umut Cihan, Arda İçöz, Vahid Haratian, Eray Tüzün
conference: "Arxiv"
year: 2025
bibkey: cihan2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20206"}
tags: ['Model Architecture', 'GPT', 'Survey Paper', 'Tools']
---
Context: Code reviews are crucial for software quality. Recent AI advances have allowed large language models (LLMs) to review and fix code; now, there are tools that perform these reviews. However, their reliability and accuracy have not yet been systematically evaluated. Objective: This study compares different LLMs' performance in detecting code correctness and suggesting improvements. Method: We tested GPT4o and Gemini 2.0 Flash on 492 AI generated code blocks of varying correctness, along with 164 canonical code blocks from the HumanEval benchmark. To simulate the code review task objectively, we expected LLMs to assess code correctness and improve the code if needed. We ran experiments with different configurations and reported on the results. Results: With problem descriptions, GPT4o and Gemini 2.0 Flash correctly classified code correctness 68.50% and 63.89% of the time, respectively, and corrected the code 67.83% and 54.26% of the time for the 492 code blocks of varying correctness. Without problem descriptions, performance declined. The results for the 164 canonical code blocks differed, suggesting that performance depends on the type of code. Conclusion: LLM code reviews can help suggest improvements and assess correctness, but there is a risk of faulty outputs. We propose a process that involves humans, called the "Human in the loop LLM Code Review" to promote knowledge sharing while mitigating the risk of faulty outputs.
