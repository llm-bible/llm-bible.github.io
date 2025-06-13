---
layout: publication
title: 'Chatasu: Evoking Llm''s Reflexion To Truly Understand Aspect Sentiment In Dialogues'
authors: Yiding Liu, Jingjing Wang, Jiamin Luo, Tao Zeng, Guodong Zhou
conference: "Arxiv"
year: 2024
bibkey: liu2024evoking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.05326'}
tags: ['Reinforcement Learning']
---
Aspect Sentiment Understanding (ASU) in interactive scenarios (e.g.,
Question-Answering and Dialogue) has attracted ever-more interest in recent
years and achieved important progresses. However, existing studies on
interactive ASU largely ignore the coreference issue for opinion targets (i.e.,
aspects), while this phenomenon is ubiquitous in interactive scenarios
especially dialogues, limiting the ASU performance. Recently, large language
models (LLMs) shows the powerful ability to integrate various NLP tasks with
the chat paradigm. In this way, this paper proposes a new Chat-based Aspect
Sentiment Understanding (ChatASU) task, aiming to explore LLMs' ability in
understanding aspect sentiments in dialogue scenarios. Particularly, this
ChatASU task introduces a sub-task, i.e., Aspect Chain Reasoning (ACR) task, to
address the aspect coreference issue. On this basis, we propose a Trusted
Self-reflexion Approach (TSA) with ChatGLM as backbone to ChatASU.
Specifically, this TSA treats the ACR task as an auxiliary task to boost the
performance of the primary ASU task, and further integrates trusted learning
into reflexion mechanisms to alleviate the LLMs-intrinsic factual hallucination
problem in TSA. Furthermore, a high-quality ChatASU dataset is annotated to
evaluate TSA, and extensive experiments show that our proposed TSA can
significantly outperform several state-of-the-art baselines, justifying the
effectiveness of TSA to ChatASU and the importance of considering the
coreference and hallucination issues in ChatASU.
