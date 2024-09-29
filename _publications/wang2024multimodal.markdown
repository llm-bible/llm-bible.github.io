---
layout: publication
title: Genartist Multimodal LLM As An Agent For Unified Image Generation And Editing
authors: Wang Zhenyu, Li Aoxue, Li Zhenguo, Liu Xihui
conference: "Arxiv"
year: 2024
bibkey: wang2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05600"}
tags: ['Agentic', 'Multimodal Models', 'Prompting', 'Tools']
---
Despite the success achieved by existing image generation and editing methods current models still struggle with complex problems including intricate text prompts and the absence of verification and self45;correction mechanisms makes the generated images unreliable. Meanwhile a single model tends to specialize in particular tasks and possess the corresponding capabilities making it inadequate for fulfilling all user requirements. We propose GenArtist a unified image generation and editing system coordinated by a multimodal large language model (MLLM) agent. We integrate a comprehensive range of existing models into the tool library and utilize the agent for tool selection and execution. For a complex problem the MLLM agent decomposes it into simpler sub45;problems and constructs a tree structure to systematically plan the procedure of generation editing and self45;correction with step45;by45;step verification. By automatically generating missing position45;related inputs and incorporating position information the appropriate tool can be effectively employed to address each sub45;problem. Experiments demonstrate that GenArtist can perform various generation and editing tasks achieving state45;of45;the45;art performance and surpassing existing models such as SDXL and DALL45;E 3 as can be seen in Fig. 1. Project page is https://zhenyuw16.github.io/GenArtist&#95;page.
