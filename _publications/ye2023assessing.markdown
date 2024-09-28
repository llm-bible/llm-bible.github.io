---
layout: publication
title: Assessing Hidden Risks of LLMs An Empirical Study on Robustness Consistency and Credibility
authors: Ye Wentao, Ou Mingfeng, Li Tianyi, Chen Yipeng, Ma Xuetao, Yanggong Yifan, Wu Sai, Fu Jie, Chen Gang, Wang Haobo, Zhao Junbo
conference: "Arxiv"
year: 2023
bibkey: ye2023assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.10235"}
tags: ['ARXIV', 'Chatgpt', 'GPT', 'LLM', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Tools']
---
The recent popularity of large language models (LLMs) has brought a significant impact to boundless fields particularly through their open-ended ecosystem such as the APIs open-sourced models and plugins. However with their widespread deployment there is a general lack of research that thoroughly discusses and analyzes the potential risks concealed. In that case we intend to conduct a preliminary but pioneering study covering the robustness consistency and credibility of LLMs systems. With most of the related literature in the era of LLM uncharted we propose an automated workflow that copes with an upscaled number of queries/responses. Overall we conduct over a million queries to the mainstream LLMs including ChatGPT LLaMA and OPT. Core to our workflow consists of a data primitive followed by an automated interpreter that evaluates these LLMs under different adversarial metrical systems. As a result we draw several and perhaps unfortunate conclusions that are quite uncommon from this trendy community. Briefly they are (i)-the minor but inevitable error occurrence in the user-generated query input may by chance cause the LLM to respond unexpectedly; (ii)-LLMs possess poor consistency when processing semantically similar query input. In addition as a side finding we find that ChatGPT is still capable to yield the correct answer even when the input is polluted at an extreme level. While this phenomenon demonstrates the powerful memorization of the LLMs it raises serious concerns about using such data for LLM-involved evaluation in academic development. To deal with it we propose a novel index associated with a dataset that roughly decides the feasibility of using such data for LLM-involved evaluation. Extensive empirical studies are tagged to support the aforementioned claims.
