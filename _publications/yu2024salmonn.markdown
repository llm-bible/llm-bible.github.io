---
layout: publication
title: 'Salmonn-omni: A Codec-free LLM For Full-duplex Speech Understanding And Generation'
authors: Wenyi Yu, Siyin Wang, Xiaoyu Yang, Xianzhao Chen, Xiaohai Tian, Jun Zhang, Guangzhi Sun, Lu Lu, Yuxuan Wang, Chao Zhang
conference: "Arxiv"
year: 2024
bibkey: yu2024salmonn
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18138"}
tags: ['Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG', 'Applications', 'INTERSPEECH']
---
Full-duplex multimodal large language models (LLMs) provide a unified
framework for addressing diverse speech understanding and generation tasks,
enabling more natural and seamless human-machine conversations. Unlike
traditional modularised conversational AI systems, which separate speech
recognition, understanding, and text-to-speech generation into distinct
components, multimodal LLMs operate as single end-to-end models. This
streamlined design eliminates error propagation across components and fully
leverages the rich non-verbal information embedded in input speech signals. We
introduce SALMONN-omni, a codec-free, full-duplex speech understanding and
generation model capable of simultaneously listening to its own generated
speech and background sounds while speaking. To support this capability, we
propose a novel duplex spoken dialogue framework incorporating a ``thinking''
mechanism that facilitates asynchronous text and speech generation relying on
embeddings instead of codecs (quantized speech and audio tokens). Experimental
results demonstrate SALMONN-omni's versatility across a broad range of
streaming speech tasks, including speech recognition, speech enhancement, and
spoken question answering. Additionally, SALMONN-omni excels at managing
turn-taking, barge-in, and echo cancellation scenarios, establishing its
potential as a robust prototype for full-duplex conversational AI systems. To
the best of our knowledge, SALMONN-omni is the first codec-free model of its
kind. A full technical report along with model checkpoints will be released
soon.
