---
layout: publication
title: Enhancing Visual Question Answering Through Question45;driven Image Captions As Prompts
authors: Özdemir Övgü, Akagündüz Erdem
conference: "Arxiv"
year: 2024
bibkey: özdemir2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08589"}
  - {name: "Code", url: "https://github.com/ovguyo/captions&#45;in&#45;VQA&#125;"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Visual question answering (VQA) is known as an AI45;complete task as it requires understanding reasoning and inferring about the vision and the language content. Over the past few years numerous neural architectures have been suggested for the VQA problem. However achieving success in zero45;shot VQA remains a challenge due to its requirement for advanced generalization and reasoning skills. This study explores the impact of incorporating image captioning as an intermediary process within the VQA pipeline. Specifically we explore the efficacy of utilizing image captions instead of images and leveraging large language models (LLMs) to establish a zero45;shot setting. Since image captioning is the most crucial step in this process we compare the impact of state45;of45;the45;art image captioning models on VQA performance across various question types in terms of structure and semantics. We propose a straightforward and efficient question45;driven image captioning approach within this pipeline to transfer contextual information into the question45;answering (QA) model. This method involves extracting keywords from the question generating a caption for each image45;question pair using the keywords and incorporating the question45;driven caption into the LLM prompt. We evaluate the efficacy of using general45;purpose and question45;driven image captions in the VQA pipeline. Our study highlights the potential of employing image captions and harnessing the capabilities of LLMs to achieve competitive performance on GQA under the zero45;shot setting. Our code is available at url123;https://github.com/ovguyo/captions&#45;in&#45;VQA&#125;.
