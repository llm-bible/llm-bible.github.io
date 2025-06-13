---
layout: publication
title: 'Towards Safer Pretraining: Analyzing And Filtering Harmful Content In Webscale Datasets For Responsible Llms'
authors: Sai Krishna Mendu, Harish Yenala, Aditi Gulati, Shanu Kumar, Parag Agrawal
conference: "Arxiv"
year: 2025
bibkey: mendu2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.02009'}
tags: ['Transformer', 'RAG', 'Security', 'Model Architecture', 'Applications', 'Training Techniques', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias', 'Responsible AI', 'Pretraining Methods']
---
Large language models (LLMs) have become integral to various real-world applications, leveraging massive, web-sourced datasets like Common Crawl, C4, and FineWeb for pretraining. While these datasets provide linguistic data essential for high-quality natural language generation, they often contain harmful content, such as hate speech, misinformation, and biased narratives. Training LLMs on such unfiltered data risks perpetuating toxic behaviors, spreading misinformation, and amplifying societal biases which can undermine trust in LLM-driven applications and raise ethical concerns about their use. This paper presents a large-scale analysis of inappropriate content across these datasets, offering a comprehensive taxonomy that categorizes harmful webpages into Topical and Toxic based on their intent. We also introduce a prompt evaluation dataset, a high-accuracy Topical and Toxic Prompt (TTP), and a transformer-based model (HarmFormer) for harmful content filtering. Additionally, we create a new multi-harm open-ended toxicity benchmark (HAVOC) and provide crucial insights into how models respond to adversarial toxic inputs. We share TTP, TTP-Eval, HAVOC and a sample of C4 inferenced on HarmFormer. Our work offers insights into ensuring safer LLM pretraining and serves as a resource for Responsible AI (RAI) compliance.
