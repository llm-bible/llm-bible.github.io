---
layout: publication
title: Training With paraphrasing The Original Text Improves Long45;context Performance
authors: Yu Yijiong, Huang Yongfeng, Qi Zhixiao, Zhou Zhe
conference: "Arxiv"
year: 2023
bibkey: yu2023training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.11193"}
tags: ['Ethics And Bias', 'RAG', 'Training Techniques']
---
As Large Language Models (LLMs) continue to evolve more are being designed to handle long45;context inputs. Despite this advancement most of them still face challenges in accurately handling long45;context tasks often showing the lost in the middle issue. We identify that insufficient retrieval capability is one of the important reasons for this issue. To tackle this challenge we propose a novel approach to design training data for long45;context tasks aiming at augmenting LLMs proficiency in extracting key information from long context. Specially we incorporate an additional part named paraphrasing the original text when constructing the answer of training samples and then fine45;tuning the model. Experimenting on LongBench and NaturalQuestions Multi45;document45;QA dataset with models of Llama and Qwen series our method achieves an improvement of up to 8.4837; and 4.4837; in average scores respectively showing effectiveness in improving the model s performance on long45;context tasks. The model and training data have been made available on HuggingFace(https://huggingface.co/yuyijiong/Qwen&#45;14b&#45;chat&#45;yarn&#45;32k).
