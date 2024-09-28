---
layout: publication
title: Harmonic LLMs are Trustworthy
authors: Kersting Nicholas S., Rahman Mohammad, Vedala Suchismitha, Wang Yang
conference: "Arxiv"
year: 2024
bibkey: kersting2024harmonic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.19708"}
tags: ['ARXIV', 'Chatgpt', 'GPT', 'Interpretability', 'Interpretability And Interpretability', 'LLM', 'Model Architecture', 'Prompting', 'Security']
---
We introduce an intuitive method to test the robustness (stability and explainability) of any black-box LLM in real-time via its local deviation from harmoniticity denoted as gamma. To the best of our knowledge this is the first completely model-agnostic and unsupervised method of measuring the robustness of any given response from an LLM based upon the model itself conforming to a purely mathematical standard. To show general application and immediacy of results we measure gamma in 10 popular LLMs (ChatGPT Claude-2.1 Claude3.0 GPT-4 GPT-4o Smaug-72B Mixtral-8x7B Llama2-7B Mistral-7B and MPT-7B) across thousands of queries in three objective domains WebQA ProgrammingQA and TruthfulQA. Across all models and domains tested human annotation confirms that gamma to 0 indicates trustworthiness and conversely searching higher values of gamma easily exposes examples of hallucination a fact that enables efficient adversarial prompt generation through stochastic gradient ascent in gamma. The low-gamma leaders among the models in the respective domains are GPT-4o GPT-4 and Smaug-72B providing evidence that mid-size open-source models can win out against large commercial models.
