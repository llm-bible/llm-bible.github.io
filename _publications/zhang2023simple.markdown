---
layout: publication
title: A Simple LLM Framework for Long-Range Video Question-Answering
authors: Zhang Ce, Lu Taixi, Islam Md Mohaiminul, Wang Ziyang, Yu Shoubin, Bansal Mohit, Bertasius Gedas
conference: "Arxiv"
year: 2023
bibkey: zhang2023simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17235"}
  - {name: "Code", url: "https://github.com/CeeZh/LLoVi"}
tags: ['Applications', 'Arxiv', 'Has Code', 'LLM', 'GPT', 'A']
---
We present LLoVi a language-based framework for long-range video question-answering (LVQA). Unlike prior long-range video understanding methods which are often costly and require specialized long-range video modeling design (e.g. memory queues state-space layers etc.) our approach uses a frame/clip-level visual captioner (e.g. BLIP2 LaViLa LLaVA) coupled with a Large Language Model (GPT-3.5 GPT-4) leading to a simple yet surprisingly effective LVQA framework. Specifically we decompose short and long-range modeling aspects of LVQA into two stages. First we use a short-term visual captioner to generate textual descriptions of short video clips (0.5-8s in length) densely sampled from a long input video. Afterward an LLM aggregates the densely extracted short-term captions to perform long-range temporal reasoning needed to understand the whole video and answer a question. To analyze what makes our simple framework so effective we thoroughly evaluate various components of our system. Our empirical analysis reveals that the choice of the visual captioner and LLM is critical for good LVQA performance. Furthermore we show that a specialized prompt that asks the LLM first to summarize the noisy short-term visual captions and then answer a given input question leads to a significant LVQA performance boost. On EgoSchema which is best known as a very long-form video question-answering benchmark our method achieves 50.3 accuracy outperforming the previous best-performing approach by 18.1 (absolute gain). In addition our approach outperforms the previous state-of-the-art by 4.1 and 3.1 on NeXT-QA and IntentQA. We also extend LLoVi to grounded LVQA and show that it outperforms all prior methods on the NeXT-GQA dataset. We will release our code at https://github.com/CeeZh/LLoVi.
