---
layout: publication
title: A Simple LLM Framework For Long45;range Video Question45;answering
authors: Zhang Ce, Lu Taixi, Islam Md Mohaiminul, Wang Ziyang, Yu Shoubin, Bansal Mohit, Bertasius Gedas
conference: "Arxiv"
year: 2023
bibkey: zhang2023simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17235"}
  - {name: "Code", url: "https://github.com/CeeZh/LLoVi"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Tools']
---
We present LLoVi a language45;based framework for long45;range video question45;answering (LVQA). Unlike prior long45;range video understanding methods which are often costly and require specialized long45;range video modeling design (e.g. memory queues state45;space layers etc.) our approach uses a frame/clip45;level visual captioner (e.g. BLIP2 LaViLa LLaVA) coupled with a Large Language Model (GPT45;3.5 GPT45;4) leading to a simple yet surprisingly effective LVQA framework. Specifically we decompose short and long45;range modeling aspects of LVQA into two stages. First we use a short45;term visual captioner to generate textual descriptions of short video clips (0.545;8s in length) densely sampled from a long input video. Afterward an LLM aggregates the densely extracted short45;term captions to perform long45;range temporal reasoning needed to understand the whole video and answer a question. To analyze what makes our simple framework so effective we thoroughly evaluate various components of our system. Our empirical analysis reveals that the choice of the visual captioner and LLM is critical for good LVQA performance. Furthermore we show that a specialized prompt that asks the LLM first to summarize the noisy short45;term visual captions and then answer a given input question leads to a significant LVQA performance boost. On EgoSchema which is best known as a very long45;form video question45;answering benchmark our method achieves 50.337; accuracy outperforming the previous best45;performing approach by 18.137; (absolute gain). In addition our approach outperforms the previous state45;of45;the45;art by 4.137; and 3.137; on NeXT45;QA and IntentQA. We also extend LLoVi to grounded LVQA and show that it outperforms all prior methods on the NeXT45;GQA dataset. We will release our code at https://github.com/CeeZh/LLoVi.
