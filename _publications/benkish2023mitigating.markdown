---
layout: publication
title: Mitigating Open45;vocabulary Caption Hallucinations
authors: Assaf Ben-kish, Moran Yanuka, Morris Alper, Raja Giryes, Hadar Averbuch-elor
conference: "Arxiv"
year: 2023
bibkey: benkish2023mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2312.03631v3"}
tags: ['Agentic', 'Applications', 'Language Modeling', 'RAG', 'Reinforcement Learning', 'Tools']
---
While recent years have seen rapid progress in image45;conditioned text generation image captioning still suffers from the fundamental issue of hallucinations namely the generation of spurious details that cannot be inferred from the given image. Existing methods largely use closed45;vocabulary object lists to mitigate or evaluate hallucinations in image captioning ignoring the long45;tailed nature of hallucinations that occur in practice. To this end we propose a framework for addressing hallucinations in image captioning in the open45;vocabulary setting. Our framework includes a new benchmark OpenCHAIR that leverages generative foundation models to evaluate open45;vocabulary object hallucinations for image captioning surpassing the popular and similarly45;sized CHAIR benchmark in both diversity and accuracy. Furthermore to mitigate open45;vocabulary hallucinations without using a closed object list we propose MOCHa an approach harnessing advancements in reinforcement learning. Our multi45;objective reward function explicitly targets the trade45;off between fidelity and adequacy in generations without requiring any strong supervision. MOCHa improves a large variety of image captioning models as captured by our OpenCHAIR benchmark and other existing metrics. We will release our code and models.
