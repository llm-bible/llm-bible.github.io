---
layout: publication
title: 'Meddoc-bot: A Chat Tool For Comparative Analysis Of Large Language Models In The Context Of The Pediatric Hypertension Guideline'
authors: Jabarulla Mohamed Yaseen, Oeltze-jafra Steffen, Beerbaum Philipp, Uden Theodor
conference: "Arxiv"
year: 2024
bibkey: jabarulla2024meddoc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.03359"}
  - {name: "Code", url: "https://github.com/yaseen28/MedDoc-Bot"}
tags: ['Has Code', 'RAG', 'Tools', 'Uncategorized']
---
This research focuses on evaluating the non-commercial open-source large
language models (LLMs) Meditron, MedAlpaca, Mistral, and Llama-2 for their
efficacy in interpreting medical guidelines saved in PDF format. As a specific
test scenario, we applied these models to the guidelines for hypertension in
children and adolescents provided by the European Society of Cardiology (ESC).
Leveraging Streamlit, a Python library, we developed a user-friendly medical
document chatbot tool (MedDoc-Bot). This tool enables authorized users to
upload PDF files and pose questions, generating interpretive responses from
four locally stored LLMs. A pediatric expert provides a benchmark for
evaluation by formulating questions and responses extracted from the ESC
guidelines. The expert rates the model-generated responses based on their
fidelity and relevance. Additionally, we evaluated the METEOR and chrF metric
scores to assess the similarity of model responses to reference answers. Our
study found that Llama-2 and Mistral performed well in metrics evaluation.
However, Llama-2 was slower when dealing with text and tabular data. In our
human evaluation, we observed that responses created by Mistral, Meditron, and
Llama-2 exhibited reasonable fidelity and relevance. This study provides
valuable insights into the strengths and limitations of LLMs for future
developments in medical document interpretation. Open-Source Code:
https://github.com/yaseen28/MedDoc-Bot
