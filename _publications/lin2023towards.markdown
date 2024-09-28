---
layout: publication
title: Towards Language-guided Interactive 3D Generation LLMs as Layout Interpreter with Generative Feedback
authors: Lin Yiqi, Wu Hao, Wang Ruichen, Lu Haonan, Lin Xiaodong, Xiong Hui, Wang Lin
conference: "Arxiv"
year: 2023
bibkey: lin2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15808"}
tags: ['ARXIV', 'Applications']
---
Generating and editing a 3D scene guided by natural language poses a challenge primarily due to the complexity of specifying the positional relations and volumetric changes within the 3D space. Recent advancements in Large Language Models (LLMs) have demonstrated impressive reasoning conversational and zero-shot generation abilities across various domains. Surprisingly these models also show great potential in realizing and interpreting the 3D space. In light of this we propose a novel language-guided interactive 3D generation system dubbed LI3D that integrates LLMs as a 3D layout interpreter into the off-the-shelf layout-to-3D generative models allowing users to flexibly and interactively generate visual content. Specifically we design a versatile layout structure base on the bounding boxes and semantics to prompt the LLMs to model the spatial generation and reasoning from language. Our system also incorporates LLaVA a large language and vision assistant to provide generative feedback from the visual aspect for improving the visual quality of generated content. We validate the effectiveness of LI3D primarily in 3D generation and editing through multi-round interactions which can be flexibly extended to 2D generation and editing. Various experiments demonstrate the potential benefits of incorporating LLMs in generative AI for applications e.g. metaverse. Moreover we benchmark the layout reasoning performance of LLMs with neural visual artist tasks revealing their emergent ability in the spatial layout domain.
