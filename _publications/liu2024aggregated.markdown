---
layout: publication
title: 'Aggregated Knowledge Model: Enhancing Domain-specific QA With Fine-tuned And Retrieval-augmented Generation Models'
authors: Fengchen Liu, Jordan Jung, Wei Feinstein, Jeff Dambrogia, Gary Jung
conference: "Arxiv"
year: 2024
bibkey: liu2024aggregated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18344"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
This paper introduces a novel approach to enhancing closed-domain Question
Answering (QA) systems, focusing on the specific needs of the Lawrence Berkeley
National Laboratory (LBL) Science Information Technology (ScienceIT) domain.
Utilizing a rich dataset derived from the ScienceIT documentation, our study
embarks on a detailed comparison of two fine-tuned large language models and
five retrieval-augmented generation (RAG) models. Through data processing
techniques, we transform the documentation into structured
context-question-answer triples, leveraging the latest Large Language Models
(AWS Bedrock, GCP PaLM2, Meta LLaMA2, OpenAI GPT-4, Google Gemini-Pro) for
data-driven insights. Additionally, we introduce the Aggregated Knowledge Model
(AKM), which synthesizes responses from the seven models mentioned above using
K-means clustering to select the most representative answers. The evaluation of
these models across multiple metrics offers a comprehensive look into their
effectiveness and suitability for the LBL ScienceIT environment. The results
demonstrate the potential benefits of integrating fine-tuning and
retrieval-augmented strategies, highlighting significant performance
improvements achieved with the AKM. The insights gained from this study can be
applied to develop specialized QA systems tailored to specific domains.
