---
layout: publication
title: Jailbreaking Text45;to45;image Models With Llm45;based Agents
authors: Dong Yingkai, Li Zheng, Meng Xiangtao, Yu Ning, Guo Shanqing
conference: "Arxiv"
year: 2024
bibkey: dong2024jailbreaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.00523"}
tags: ['Agent', 'Agentic', 'Efficiency And Optimization', 'Prompting', 'RAG', 'Responsible AI', 'Security', 'Tools']
---
Recent advancements have significantly improved automated task45;solving capabilities using autonomous agents powered by large language models (LLMs). However most LLM45;based agents focus on dialogue programming or specialized domains leaving their potential for addressing generative AI safety tasks largely unexplored. In this paper we propose Atlas an advanced LLM45;based multi45;agent framework targeting generative AI models specifically focusing on jailbreak attacks against text45;to45;image (T2I) models with built45;in safety filters. Atlas consists of two agents namely the mutation agent and the selection agent each comprising four key modules a vision45;language model (VLM) or LLM brain planning memory and tool usage. The mutation agent uses its VLM brain to determine whether a prompt triggers the T2I models safety filter. It then collaborates iteratively with the LLM brain of the selection agent to generate new candidate jailbreak prompts with the highest potential to bypass the filter. In addition to multi45;agent communication we leverage in45;context learning (ICL) memory mechanisms and the chain45;of45;thought (COT) approach to learn from past successes and failures thereby enhancing Atlass performance. Our evaluation demonstrates that Atlas successfully jailbreaks several state45;of45;the45;art T2I models equipped with multi45;modal safety filters in a black45;box setting. Additionally Atlas outperforms existing methods in both query efficiency and the quality of generated images. This work convincingly demonstrates the successful application of LLM45;based agents in studying the safety vulnerabilities of popular text45;to45;image generation models. We urge the community to consider advanced techniques like ours in response to the rapidly evolving text45;to45;image generation field.
