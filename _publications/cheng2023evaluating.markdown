---
layout: publication
title: Evaluating Hallucinations In Chinese Large Language Models
authors: Cheng Qinyuan, Sun Tianxiang, Zhang Wenwei, Wang Siyin, Liu Xiangyang, Zhang Mozhi, He Junliang, Huang Mianqiu, Yin Zhangyue, Chen Kai, Qiu Xipeng
conference: "Arxiv"
year: 2023
bibkey: cheng2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03368"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Security']
---
In this paper we establish a benchmark named HalluQA (Chinese Hallucination Question-Answering) to measure the hallucination phenomenon in Chinese large language models. HalluQA contains 450 meticulously designed adversarial questions spanning multiple domains and takes into account Chinese historical culture customs and social phenomena. During the construction of HalluQA we consider two types of hallucinations imitative falsehoods and factual errors and we construct adversarial samples based on GLM-130B and ChatGPT. For evaluation we design an automated evaluation method using GPT-4 to judge whether a model output is hallucinated. We conduct extensive experiments on 24 large language models including ERNIE-Bot Baichuan2 ChatGLM Qwen SparkDesk and etc. Out of the 24 models 18 achieved non-hallucination rates lower than 5037;. This indicates that HalluQA is highly challenging. We analyze the primary types of hallucinations in different types of models and their causes. Additionally we discuss which types of hallucinations should be prioritized for different types of models.
