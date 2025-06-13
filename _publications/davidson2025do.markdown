---
layout: publication
title: 'Do Different Prompting Methods Yield A Common Task Representation In Language Models?'
authors: Guy Davidson, Todd M. Gureckis, Brenden M. Lake, Adina Williams
conference: "Arxiv"
year: 2025
bibkey: davidson2025do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12075"}
tags: ['Few-Shot', 'Reinforcement Learning', 'RAG', 'Interpretability and Explainability', 'Prompting', 'In-Context Learning']
---
Demonstrations and instructions are two primary approaches for prompting language models to perform in-context learning (ICL) tasks. Do identical tasks elicited in different ways result in similar representations of the task? An improved understanding of task representation mechanisms would offer interpretability insights and may aid in steering models. We study this through \textit\{function vectors\} (FVs), recently proposed as a mechanism to extract few-shot ICL task representations. We generalize FVs to alternative task presentations, focusing on short textual instruction prompts, and successfully extract instruction function vectors that promote zero-shot task accuracy. We find evidence that demonstration- and instruction-based function vectors leverage different model components, and offer several controls to dissociate their contributions to task performance. Our results suggest that different task promptings forms do not induce a common task representation through FVs but elicit different, partly overlapping mechanisms. Our findings offer principled support to the practice of combining instructions and task demonstrations, imply challenges in universally monitoring task inference across presentation forms, and encourage further examinations of LLM task inference mechanisms.
