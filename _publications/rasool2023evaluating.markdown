---
layout: publication
title: "Evaluating Llms On Document-based QA: Exact Answer Selection And Numerical Extraction Using Cogtale Dataset"
authors: Rasool Zafaryab, Kurniawan Stefanus, Balugo Sherwin, Barnett Scott, Vasa Rajesh, Chesser Courtney, Hampstead Benjamin M., Belleville Sylvie, Mouzakis Kon, Bahar-fuchs Alex
conference: "Arxiv"
year: 2023
bibkey: rasool2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07878"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Survey Paper', 'Tools']
---
Document-based Question-Answering (QA) tasks are crucial for precise information retrieval. While some existing work focus on evaluating large language models performance on retrieving and answering questions from documents assessing the LLMs performance on QA types that require exact answer selection from predefined options and numerical extraction is yet to be fully assessed. In this paper we specifically focus on this underexplored context and conduct empirical analysis of LLMs (GPT-4 and GPT-3.5) on question types including single-choice yes-no multiple-choice and number extraction questions from documents in zero-shot setting. We use the CogTale dataset for evaluation which provide human expert-tagged responses offering a robust benchmark for precision and factual grounding. We found that LLMs particularly GPT-4 can precisely answer many single-choice and yes-no questions given relevant context demonstrating their efficacy in information retrieval tasks. However their performance diminishes when confronted with multiple-choice and number extraction formats lowering the overall performance of the model on this task indicating that these models may not yet be sufficiently reliable for the task. This limits the applications of LLMs on applications demanding precise information extraction from documents such as meta-analysis tasks. These findings hinge on the assumption that the retrievers furnish pertinent context necessary for accurate responses emphasizing the need for further research. Our work offers a framework for ongoing dataset evaluation ensuring that LLM applications for information retrieval and document analysis continue to meet evolving standards.
