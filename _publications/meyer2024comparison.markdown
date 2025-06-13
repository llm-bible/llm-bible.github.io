---
layout: publication
title: 'A Comparison Of LLM Finetuning Methods & Evaluation Metrics With Travel Chatbot Use Case'
authors: Sonia Meyer, Shreya Singh, Bertha Tam, Christopher Ton, Angel Ren
conference: "Arxiv"
year: 2024
bibkey: meyer2024comparison
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03562"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
This research compares large language model (LLM) fine-tuning methods,
including Quantized Low Rank Adapter (QLoRA), Retrieval Augmented fine-tuning
(RAFT), and Reinforcement Learning from Human Feedback (RLHF), and additionally
compared LLM evaluation methods including End to End (E2E) benchmark method of
"Golden Answers", traditional natural language processing (NLP) metrics, RAG
Assessment (Ragas), OpenAI GPT-4 evaluation metrics, and human evaluation,
using the travel chatbot use case. The travel dataset was sourced from the the
Reddit API by requesting posts from travel-related subreddits to get
travel-related conversation prompts and personalized travel experiences, and
augmented for each fine-tuning method. We used two pretrained LLMs utilized for
fine-tuning research: LLaMa 2 7B, and Mistral 7B. QLoRA and RAFT are applied to
the two pretrained models. The inferences from these models are extensively
evaluated against the aforementioned metrics. The best model according to human
evaluation and some GPT-4 metrics was Mistral RAFT, so this underwent a
Reinforcement Learning from Human Feedback (RLHF) training pipeline, and
ultimately was evaluated as the best model. Our main findings are that: 1)
quantitative and Ragas metrics do not align with human evaluation, 2) Open AI
GPT-4 evaluation most aligns with human evaluation, 3) it is essential to keep
humans in the loop for evaluation because, 4) traditional NLP metrics
insufficient, 5) Mistral generally outperformed LLaMa, 6) RAFT outperforms
QLoRA, but still needs postprocessing, 7) RLHF improves model performance
significantly. Next steps include improving data quality, increasing data
quantity, exploring RAG methods, and focusing data collection on a specific
city, which would improve data quality by narrowing the focus, while creating a
useful product.
