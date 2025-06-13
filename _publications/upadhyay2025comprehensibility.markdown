---
layout: publication
title: 'On The Comprehensibility Of Multi-structured Financial Documents Using Llms And Pre-processing Tools'
authors: Shivani Upadhyay, Messiah Ataey, Shariyar Murtuza, Yifan Nie, Jimmy Lin
conference: "Arxiv"
year: 2025
bibkey: upadhyay2025comprehensibility
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.05182"}
  - {name: "Code", url: "https://github.com/OGCDS/FinancialQA"}
tags: ['Tools', 'GPT', 'RAG', 'Model Architecture', 'Has Code']
---
The proliferation of complex structured data in hybrid sources, such as PDF documents and web pages, presents unique challenges for current Large Language Models (LLMs) and Multi-modal Large Language Models (MLLMs) in providing accurate answers. Despite the recent advancements of MLLMs, they still often falter when interpreting intricately structured information, such as nested tables and multi-dimensional plots, leading to hallucinations and erroneous outputs. This paper explores the capabilities of LLMs and MLLMs in understanding and answering questions from complex data structures found in PDF documents by leveraging industrial and open-source tools as part of a pre-processing pipeline. Our findings indicate that GPT-4o, a popular MLLM, achieves an accuracy of 56% on multi-structured documents when fed documents directly, and that integrating pre-processing tools raises the accuracy of LLMs to 61.3% for GPT-4o and 76% for GPT-4, and with lower overall cost. The code is publicly available at https://github.com/OGCDS/FinancialQA.
