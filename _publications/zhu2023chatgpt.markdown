---
layout: publication
title: Chatgpt Asks BLIP45;2 Answers Automatic Questioning Towards Enriched Visual Descriptions
authors: Deyao Zhu, Jun Chen, Kilichbek Haydarov, Xiaoqian Shen, Wenxuan Zhang, Mohamed Elhoseiny
conference: "Arxiv"
year: 2023
bibkey: zhu2023chatgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2303.06594v1"}
  - {name: "Code", url: "https://github.com/Vision&#45;CAIR/ChatCaptioner"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Asking insightful questions is crucial for acquiring knowledge and expanding our understanding of the world. However the importance of questioning has been largely overlooked in AI research where models have been primarily developed to answer questions. With the recent advancements of large language models (LLMs) like ChatGPT we discover their capability to ask high45;quality questions when provided with a suitable prompt. This discovery presents a new opportunity to develop an automatic questioning system. In this paper we introduce ChatCaptioner a novel automatic45;questioning method deployed in image captioning. Here ChatGPT is prompted to ask a series of informative questions about images to BLIP45;2 a strong vision question45;answering model. By keeping acquiring new visual information from BLIP45;2s answers ChatCaptioner is able to generate more enriched image descriptions. We conduct human45;subject evaluations on common image caption datasets such as COCO Conceptual Caption and WikiArt and compare ChatCaptioner with BLIP45;2 as well as ground truth. Our results demonstrate that ChatCaptioners captions are significantly more informative receiving three times as many votes from human evaluators for providing the most image information. Besides ChatCaptioner identifies 5337; more objects within the image than BLIP45;2 alone measured by WordNet synset matching. Code is available at https://github.com/Vision&#45;CAIR/ChatCaptioner
