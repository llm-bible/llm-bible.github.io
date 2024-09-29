---
layout: publication
title: Analyzing LLM Behavior in Dialogue Summarization Unveiling Circumstantial Hallucination Trends
authors: Ramprasad Sanjana, Ferracane Elisa, Lipton Zachary C.
conference: "Arxiv"
year: 2024
bibkey: ramprasad2024analyzing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03487"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Recent advancements in large language models (LLMs) have considerably advanced the capabilities of summarization systems. However they continue to face concerns about hallucinations. While prior work has evaluated LLMs extensively in news domains most evaluation of dialogue summarization has focused on BART-based models leaving a gap in our understanding of their faithfulness. Our work benchmarks the faithfulness of LLMs for dialogue summarization using human annotations and focusing on identifying and categorizing span-level inconsistencies. Specifically we focus on two prominent LLMs GPT-4 and Alpaca-13B. Our evaluation reveals subtleties as to what constitutes a hallucination LLMs often generate plausible inferences supported by circumstantial evidence in the conversation that lack direct evidence a pattern that is less prevalent in older models. We propose a refined taxonomy of errors coining the category of Circumstantial Inference to bucket these LLM behaviors and release the dataset. Using our taxonomy we compare the behavioral differences between LLMs and older fine-tuned models. Additionally we systematically assess the efficacy of automatic error detection methods on LLM summaries and find that they struggle to detect these nuanced errors. To address this we introduce two prompt-based approaches for fine-grained error detection that outperform existing metrics particularly for identifying Circumstantial Inference.
