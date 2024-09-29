---
layout: publication
title: Element45;aware Summarization With Large Language Models Expert45;aligned Evaluation And Chain45;of45;thought Method
authors: Yiming Wang, Zhuosheng Zhang, Rui Wang
conference: "Arxiv"
year: 2023
bibkey: wang2023element
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2305.13412v1"}
  - {name: "Code", url: "https://github.com/Alsace08/SumCoT"}
tags: ['Applications', 'Has Code']
---
Automatic summarization generates concise summaries that contain key ideas of source documents. As the most mainstream datasets for the news sub45;domain CNN/DailyMail and BBC XSum have been widely used for performance benchmarking. However the reference summaries of those datasets turn out to be noisy mainly in terms of factual hallucination and information redundancy. To address this challenge we first annotate new expert45;writing Element45;aware test sets following the Lasswell Communication Model proposed by Lasswell (1948) allowing reference summaries to focus on more fine45;grained news elements objectively and comprehensively. Utilizing the new test sets we observe the surprising zero45;shot summary ability of LLMs which addresses the issue of the inconsistent results between human preference and automatic evaluation metrics of LLMs zero45;shot summaries in prior work. Further we propose a Summary Chain45;of45;Thought (SumCoT) technique to elicit LLMs to generate summaries step by step which helps them integrate more fine45;grained details of source documents into the final summaries that correlate with the human writing mindset. Experimental results show our method outperforms state45;of45;the45;art fine45;tuned PLMs and zero45;shot LLMs by +4.33/+4.77 in ROUGE45;L on the two datasets respectively. Dataset and code are publicly available at https://github.com/Alsace08/SumCoT.
