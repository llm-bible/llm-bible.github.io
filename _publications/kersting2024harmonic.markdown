---
layout: publication
title: Harmonic Llms Are Trustworthy
authors: Kersting Nicholas S., Rahman Mohammad, Vedala Suchismitha, Wang Yang
conference: "Arxiv"
year: 2024
bibkey: kersting2024harmonic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.19708"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Security']
---
We introduce an intuitive method to test the robustness (stability and explainability) of any black45;box LLM in real45;time via its local deviation from harmoniticity denoted as γ. To the best of our knowledge this is the first completely model45;agnostic and unsupervised method of measuring the robustness of any given response from an LLM based upon the model itself conforming to a purely mathematical standard. To show general application and immediacy of results we measure γ in 10 popular LLMs (ChatGPT Claude45;2.1 Claude3.0 GPT45;4 GPT45;4o Smaug45;72B Mixtral45;8x7B Llama245;7B Mistral45;7B and MPT45;7B) across thousands of queries in three objective domains WebQA ProgrammingQA and TruthfulQA. Across all models and domains tested human annotation confirms that γ to 0 indicates trustworthiness and conversely searching higher values of γ easily exposes examples of hallucination a fact that enables efficient adversarial prompt generation through stochastic gradient ascent in γ. The low45;γ leaders among the models in the respective domains are GPT45;4o GPT45;4 and Smaug45;72B providing evidence that mid45;size open45;source models can win out against large commercial models.
