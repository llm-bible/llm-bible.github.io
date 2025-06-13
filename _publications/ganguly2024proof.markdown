---
layout: publication
title: 'Proof Of Thought : Neurosymbolic Program Synthesis Allows Robust And Interpretable Reasoning'
authors: Debargha Ganguly, Srinivasan Iyengar, Vipin Chaudhary, Shivkumar Kalyanaraman
conference: "Arxiv"
year: 2024
bibkey: ganguly2024proof
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.17270"}
tags: ['Responsible AI', 'Tools', 'Applications', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'Interpretability', 'Multimodal Models']
---
Large Language Models (LLMs) have revolutionized natural language processing,
yet they struggle with inconsistent reasoning, particularly in novel domains
and complex logical sequences. This research introduces Proof of Thought, a
framework that enhances the reliability and transparency of LLM outputs. Our
approach bridges LLM-generated ideas with formal logic verification, employing
a custom interpreter to convert LLM outputs into First Order Logic constructs
for theorem prover scrutiny. Central to our method is an intermediary
JSON-based Domain-Specific Language, which by design balances precise logical
structures with intuitive human concepts. This hybrid representation enables
both rigorous validation and accessible human comprehension of LLM reasoning
processes. Key contributions include a robust type system with sort management
for enhanced logical integrity, explicit representation of rules for clear
distinction between factual and inferential knowledge, and a flexible
architecture that allows for easy extension to various domain-specific
applications. We demonstrate Proof of Thought's effectiveness through
benchmarking on StrategyQA and a novel multimodal reasoning task, showing
improved performance in open-ended scenarios. By providing verifiable and
interpretable results, our technique addresses critical needs for AI system
accountability and sets a foundation for human-in-the-loop oversight in
high-stakes domains.
