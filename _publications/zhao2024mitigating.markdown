---
layout: publication
title: Mitigating Object Hallucination In Large Vision45;language Models Via Classifier45;free Guidance
authors: Zhao Linxi, Deng Yihe, Zhang Weitong, Gu Quanquan
conference: "Arxiv"
year: 2024
bibkey: zhao2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08680"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Tools', 'Training Techniques']
---
The advancement of Large Vision45;Language Models (LVLMs) has increasingly highlighted the critical issue of their tendency to hallucinate non45;existing objects in the images. To address this issue previous works focused on using specially curated datasets or powerful LLMs (e.g. GPT45;3.5) to rectify the outputs of LVLMs. However these approaches require either expensive training/fine45;tuning or API access to advanced LLMs to correct the models output post45;generation. In this paper we tackle this challenge by introducing a framework called Mitigating hallucinAtion via classifieR45;Free guIdaNcE (MARINE) which is both training45;free and API45;free and can effectively and efficiently reduce object hallucinations during the generation process. Specifically MARINE enriches the visual context of LVLMs by integrating existing open45;source vision models and employs classifier45;free guidance to incorporate the additional object grounding features to improve the precision of LVLMs generations. Through comprehensive evaluations across 6 popular LVLMs with diverse evaluation metrics we demonstrate the effectiveness of MARINE which even outperforms existing fine45;tuning45;based methods. Remarkably it not only reduces hallucinations but also improves the detailedness of LVLMs generations as assessed by GPT45;4V.
