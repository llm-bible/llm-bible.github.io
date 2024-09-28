---
layout: publication
title: On the Intrinsic Self-Correction Capability of LLMs Uncertainty and Latent Concept
authors: Liu Guangliang, Mao Haitao, Cao Bochuan, Xue Zhiyu, Johnson Kristen, Tang Jiliang, Wang Rongrong
conference: "Arxiv"
year: 2024
bibkey: liu2024intrinsic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02378"}
tags: ['ARXIV', 'Applications', 'Bias Mitigation', 'Vision Language']
---
Large Language Models (LLMs) can improve their responses when instructed to do so a capability known as self-correction. When these instructions lack specific details about the issues in the response this is referred to as leveraging the intrinsic self-correction capability. The empirical success of self-correction can be found in various applications e.g. text detoxification and social bias mitigation. However leveraging this self-correction capability may not always be effective as it has the potential to revise an initially correct response into an incorrect one. In this paper we endeavor to understand how and why leveraging the self-correction capability is effective. We identify that appropriate instructions can guide LLMs to a convergence state wherein additional self-correction steps do not yield further performance improvements. We empirically demonstrate that model uncertainty and activated latent concepts jointly characterize the effectiveness of self-correction. Furthermore we provide a mathematical formulation indicating that the activated latent concept drives the convergence of the model uncertainty and self-correction performance. Our analysis can also be generalized to the self-correction behaviors observed in Vision-Language Models (VLMs). Moreover we highlight that task-agnostic debiasing can benefit from our principle in terms of selecting effective fine-tuning samples. Such initial success demonstrates the potential extensibility for better instruction tuning and safety alignment.
