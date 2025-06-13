---
layout: publication
title: 'Realtime QA: What''s The Answer Right Now?'
authors: Jungo Kasai, Keisuke Sakaguchi, Yoichi Takahashi, Ronan Le Bras, Akari Asai, Xinyan Yu, Dragomir Radev, Noah A. Smith, Yejin Choi, Kentaro Inui
conference: "Arxiv"
year: 2022
bibkey: kasai2022realtime
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.13332"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Applications']
---
We introduce REALTIME QA, a dynamic question answering (QA) platform that
announces questions and evaluates systems on a regular basis (weekly in this
version). REALTIME QA inquires about the current world, and QA systems need to
answer questions about novel events or information. It therefore challenges
static, conventional assumptions in open-domain QA datasets and pursues
instantaneous applications. We build strong baseline models upon large
pretrained language models, including GPT-3 and T5. Our benchmark is an ongoing
effort, and this paper presents real-time evaluation results over the past
year. Our experimental results show that GPT-3 can often properly update its
generation results, based on newly-retrieved documents, highlighting the
importance of up-to-date information retrieval. Nonetheless, we find that GPT-3
tends to return outdated answers when retrieved documents do not provide
sufficient information to find an answer. This suggests an important avenue for
future research: can an open-domain QA system identify such unanswerable cases
and communicate with the user or even the retrieval module to modify the
retrieval results? We hope that REALTIME QA will spur progress in instantaneous
applications of question answering and beyond.
