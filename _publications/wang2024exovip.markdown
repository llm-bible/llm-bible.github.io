---
layout: publication
title: Exovip Step-by-step Verification And Exploration With Exoskeleton Modules For Compositional Visual Reasoning
authors: Wang Yuxuan, Yuille Alan, Li Zhuowan, Zheng Zilong
conference: "Arxiv"
year: 2024
bibkey: wang2024exovip
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.02210"}
tags: ['Few Shot', 'Fine Tuning', 'Multimodal Models']
---
Compositional visual reasoning methods which translate a complex query into a structured composition of feasible visual tasks have exhibited a strong potential in complicated multi-modal tasks. Empowered by recent advances in large language models (LLMs) this multi-modal challenge has been brought to a new stage by treating LLMs as few-shot/zero-shot planners i.e. vision-language (VL) programming. Such methods despite their numerous merits suffer from challenges due to LLM planning mistakes or inaccuracy of visual execution modules lagging behind the non-compositional models. In this work we devise a plug-and-play method ExoViP to correct errors in both the planning and execution stages through introspective verification. We employ verification modules as exoskeletons to enhance current VL programming schemes. Specifically our proposed verification module utilizes a mixture of three sub-verifiers to validate predictions after each reasoning step subsequently calibrating the visual module predictions and refining the reasoning trace planned by LLMs. Experimental results on two representative VL programming methods showcase consistent improvements on five compositional reasoning tasks on standard benchmarks. In light of this we believe that ExoViP can foster better performance and generalization on open-domain multi-modal challenges.
