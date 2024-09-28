---
layout: publication
title: Towards Zero-Shot and Few-Shot Table Question Answering using GPT-3
authors: Srivastava Pragya, Ganu Tanuja, Guha Saikat
conference: "Arxiv"
year: 2022
bibkey: srivastava2022towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.17284"}
tags: ['GPT', 'Pretraining Methods', 'Arxiv']
---
We present very early results on using GPT-3 to perform question answering on tabular data. We find that stock pre-trained GPT-3 is able to zero-shot learn the table structure from a serialized JSON array-of-arrays representation and able to answer lookup queries and simple comparison questions in natural language without any fine-tuning. We further find that simple prompt engineering to include few-shot static QA examples significantly improves accuracy. Lastly we find that intermixing passage text improves accuracy even further on heterogeneous data. We apply our approach on a novel dataset of simple tables in newspaper infographics with promising results. Overall we find much cause for optimism in this basic approach.
