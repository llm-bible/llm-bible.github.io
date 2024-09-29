---
layout: publication
title: Promptcap Prompt45;guided Task45;aware Image Captioning
authors: Hu Yushi, Hua Hang, Yang Zhengyuan, Shi Weijia, Smith Noah A, Luo Jiebo
conference: "Arxiv"
year: 2022
bibkey: hu2022prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.09699"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Knowledge45;based visual question answering (VQA) involves questions that require world knowledge beyond the image to yield the correct answer. Large language models (LMs) like GPT45;3 are particularly helpful for this task because of their strong knowledge retrieval and reasoning capabilities. To enable LM to understand images prior work uses a captioning model to convert images into text. However when summarizing an image in a single caption sentence which visual entities to describe are often underspecified. Generic image captions often miss visual details essential for the LM to answer visual questions correctly. To address this challenge we propose PromptCap (Prompt45;guided image Captioning) a captioning model designed to serve as a better connector between images and black45;box LMs. Different from generic captions PromptCap takes a natural45;language prompt to control the visual entities to describe in the generated caption. The prompt contains a question that the caption should aid in answering. To avoid extra annotation PromptCap is trained by examples synthesized with GPT45;3 and existing datasets. We demonstrate PromptCaps effectiveness on an existing pipeline in which GPT45;3 is prompted with image captions to carry out VQA. PromptCap outperforms generic captions by a large margin and achieves state45;of45;the45;art accuracy on knowledge45;based VQA tasks (60.437; on OK45;VQA and 59.637; on A45;OKVQA). Zero45;shot results on WebQA show that PromptCap generalizes well to unseen domains.
