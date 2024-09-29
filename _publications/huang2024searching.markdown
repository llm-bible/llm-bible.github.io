---
layout: publication
title: Reason3d Searching And Reasoning 3D Segmentation Via Large Language Model
authors: Huang Kuan-chih, Li Xiangtai, Qi Lu, Yan Shuicheng, Yang Ming-hsuan
conference: "Arxiv"
year: 2024
bibkey: huang2024searching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17427"}
  - {name: "Code", url: "https://github.com/KuanchihHuang/Reason3D"}
tags: ['Applications', 'Has Code', 'Multimodal Models', 'Prompting']
---
Recent advancements in multimodal large language models (LLMs) have shown their potential in various domains especially concept reasoning. Despite these developments applications in understanding 3D environments remain limited. This paper introduces Reason3D a novel LLM designed for comprehensive 3D understanding. Reason3D takes point cloud data and text prompts as input to produce textual responses and segmentation masks facilitating advanced tasks like 3D reasoning segmentation hierarchical searching express referring and question answering with detailed mask outputs. Specifically we propose a hierarchical mask decoder to locate small objects within expansive scenes. This decoder initially generates a coarse location estimate covering the objects general area. This foundational estimation facilitates a detailed coarse45;to45;fine segmentation strategy that significantly enhances the precision of object identification and segmentation. Experiments validate that Reason3D achieves remarkable results on large45;scale ScanNet and Matterport3D datasets for 3D express referring 3D question answering and 3D reasoning segmentation tasks. Code and models are available at https://github.com/KuanchihHuang/Reason3D.
