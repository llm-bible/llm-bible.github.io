---
layout: publication
title: 'Agentclinic: A Multimodal Agent Benchmark To Evaluate AI In Simulated Clinical Environments'
authors: Samuel Schmidgall, Rojin Ziaei, Carl Harris, Eduardo Reis, Jeffrey Jopling, Michael Moor
conference: "Arxiv"
year: 2024
bibkey: schmidgall2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07960"}
tags: ['Agentic', 'Tools', 'Ethics and Bias', 'RAG', 'Reinforcement Learning', 'Multimodal Models']
---
Evaluating large language models (LLM) in clinical scenarios is crucial to assessing their potential clinical utility. Existing benchmarks rely heavily on static question-answering, which does not accurately depict the complex, sequential nature of clinical decision-making. Here, we introduce AgentClinic, a multimodal agent benchmark for evaluating LLMs in simulated clinical environments that include patient interactions, multimodal data collection under incomplete information, and the usage of various tools, resulting in an in-depth evaluation across nine medical specialties and seven languages. We find that solving MedQA problems in the sequential decision-making format of AgentClinic is considerably more challenging, resulting in diagnostic accuracies that can drop to below a tenth of the original accuracy. Overall, we observe that agents sourced from Claude-3.5 outperform other LLM backbones in most settings. Nevertheless, we see stark differences in the LLMs' ability to make use of tools, such as experiential learning, adaptive retrieval, and reflection cycles. Strikingly, Llama-3 shows up to 92% relative improvements with the notebook tool that allows for writing and editing notes that persist across cases. To further scrutinize our clinical simulations, we leverage real-world electronic health records, perform a clinical reader study, perturb agents with biases, and explore novel patient-centric metrics that this interactive environment firstly enables.
