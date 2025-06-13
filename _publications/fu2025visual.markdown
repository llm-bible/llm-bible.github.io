---
layout: publication
title: 'Refocus: Visual Editing As A Chain Of Thought For Structured Image Understanding'
authors: Xingyu Fu, Minqian Liu, Zhengyuan Yang, John Corring, Yijuan Lu, Jianwei Yang, Dan Roth, Dinei Florencio, Cha Zhang
conference: "Arxiv"
year: 2025
bibkey: fu2025visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.05452"}
tags: ['Tools', 'GPT', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models']
---
Structured image understanding, such as interpreting tables and charts,
requires strategically refocusing across various structures and texts within an
image, forming a reasoning sequence to arrive at the final answer. However,
current multimodal large language models (LLMs) lack this multihop selective
attention capability. In this work, we introduce ReFocus, a simple yet
effective framework that equips multimodal LLMs with the ability to generate
"visual thoughts" by performing visual editing on the input image through code,
shifting and refining their visual focuses. Specifically, ReFocus enables
multimodal LLMs to generate Python codes to call tools and modify the input
image, sequentially drawing boxes, highlighting sections, and masking out
areas, thereby enhancing the visual reasoning process. We experiment upon a
wide range of structured image understanding tasks involving tables and charts.
ReFocus largely improves performance on all tasks over GPT-4o without visual
editing, yielding an average gain of 11.0% on table tasks and 6.8% on chart
tasks. We present an in-depth analysis of the effects of different visual
edits, and reasons why ReFocus can improve the performance without introducing
additional information. Further, we collect a 14k training set using ReFocus,
and prove that such visual chain-of-thought with intermediate information
offers a better supervision than standard VQA data, reaching a 8.0% average
gain over the same model trained with QA pairs and 2.6% over CoT.
