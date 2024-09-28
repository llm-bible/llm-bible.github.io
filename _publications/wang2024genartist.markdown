---
layout: publication
title: GenArtist Multimodal LLM as an Agent for Unified Image Generation and Editing
authors: Wang Zhenyu, Li Aoxue, Li Zhenguo, Liu Xihui
conference: "Arxiv"
year: 2024
bibkey: wang2024genartist
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05600"}
tags: ['LLM', 'Multimodal Models', 'Arxiv']
---
Despite the success achieved by existing image generation and editing methods current models still struggle with complex problems including intricate text prompts and the absence of verification and self-correction mechanisms makes the generated images unreliable. Meanwhile a single model tends to specialize in particular tasks and possess the corresponding capabilities making it inadequate for fulfilling all user requirements. We propose GenArtist a unified image generation and editing system coordinated by a multimodal large language model (MLLM) agent. We integrate a comprehensive range of existing models into the tool library and utilize the agent for tool selection and execution. For a complex problem the MLLM agent decomposes it into simpler sub-problems and constructs a tree structure to systematically plan the procedure of generation editing and self-correction with step-by-step verification. By automatically generating missing position-related inputs and incorporating position information the appropriate tool can be effectively employed to address each sub-problem. Experiments demonstrate that GenArtist can perform various generation and editing tasks achieving state-of-the-art performance and surpassing existing models such as SDXL and DALL-E 3 as can be seen in Fig. 1. Project page is https://zhenyuw16.github.io/GenArtist_page.
