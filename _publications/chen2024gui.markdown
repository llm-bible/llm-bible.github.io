---
layout: publication
title: 'GUI-WORLD: A Dataset For Gui-oriented Multimodal Llm-based Agents'
authors: Chen Dongping, Huang Yue, Wu Siyuan, Tang Jingyu, Chen Liuyi, Bai Yilin, He Zhigang, Wang Chenlong, Zhou Huichi, Li Yiqiang, Zhou Tianshuo, Yu Yue, Gao Chujie, Zhang Qihui, Gui Yi, Li Zhen, Wan Yao, Zhou Pan, Gao Jianfeng, Sun Lichao
conference: "Arxiv"
year: 2024
bibkey: chen2024gui
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10819"}
  - {name: "Code", url: "https://gui-world.github.io/"}
tags: ['Agentic', 'Has Code', 'Multimodal Models', 'RAG', 'Reinforcement Learning']
---
"Recently, Multimodal Large Language Models (MLLMs) have been used as agents to control keyboard and mouse inputs by directly perceiving the Graphical User Interface (GUI) and generating corresponding code. However, current agents primarily exhibit excellent understanding capabilities in static environments and are predominantly applied in relatively simple domains, such as Web or mobile interfaces. We argue that a robust GUI agent should be capable of perceiving temporal information on the GUI, including dynamic Web content and multi-step tasks. Additionally, it should possess a comprehensive understanding of various GUI scenarios, including desktop software and multi-window interactions. To this end, this paper introduces a new dataset, termed GUI-World, which features meticulously crafted Human-MLLM annotations, extensively covering six GUI scenarios and eight types of GUI-oriented questions in three formats. We evaluate the capabilities of current state-of-the-art MLLMs, including ImageLLMs and VideoLLMs, in understanding various types of GUI content, especially dynamic and sequential content. Our findings reveal that ImageLLMs struggle with dynamic GUI content without manually annotated keyframes or operation history. On the other hand, VideoLLMs fall short in all GUI-oriented tasks given the sparse GUI video dataset. Based on GUI-World, we take the initial step of leveraging a fine-tuned VideoLLM as a GUI agent, demonstrating an improved understanding of various GUI tasks. However, due to the limitations in the performance of base LLMs, we conclude that using VideoLLMs as GUI agents remains a significant challenge. We believe our work provides valuable insights for future research in dynamic GUI content understanding. The code and dataset are publicly available at our project homepage: https://gui-world.github.io/."
