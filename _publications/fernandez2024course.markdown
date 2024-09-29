---
layout: publication
title: Syllabusqa&#58; A Course Logistics Question Answering Dataset
authors: Fernandez Nigel, Scarlatos Alexander, Lan Andrew
conference: "Arxiv"
year: 2024
bibkey: fernandez2024course
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14666"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG']
---
Automated teaching assistants and chatbots have significant potential to reduce the workload of human instructors especially for logistics-related question answering which is important to students yet repetitive for instructors. However due to privacy concerns there is a lack of publicly available datasets. We introduce SyllabusQA an open-source dataset with 63 real course syllabi covering 36 majors containing 5078 open-ended course logistics-related question-answer pairs that are diverse in both question types and answer formats. Since many logistics-related questions contain critical information like the date of an exam it is important to evaluate the factuality of answers. We benchmark several strong baselines on this task from large language model prompting to retrieval-augmented generation. We introduce Fact-QA an LLM-based (GPT-4) evaluation metric to evaluate the factuality of predicted answers. We find that despite performing close to humans on traditional metrics of textual similarity there remains a significant gap between automated approaches and humans in terms of fact precision.
