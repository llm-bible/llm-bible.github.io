---
layout: publication
title: Multi45;modal Instruction Tuned Llms With Fine45;grained Visual Perception
authors: He Junwen, Wang Yifan, Wang Lijun, Lu Huchuan, He Jun-yan, Lan Jin-peng, Luo Bin, Xie Xuansong
conference: "Arxiv"
year: 2024
bibkey: he2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02969"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Multimodal Large Language Model (MLLMs) leverages Large Language Models as a cognitive framework for diverse visual45;language tasks. Recent efforts have been made to equip MLLMs with visual perceiving and grounding capabilities. However there still remains a gap in providing fine45;grained pixel45;level perceptions and extending interactions beyond text45;specific inputs. In this work we propose 123;bf123;AnyRef125;125; a general MLLM model that can generate pixel45;wise object perceptions and natural language descriptions from multi45;modality references such as texts boxes images or audio. This innovation empowers users with greater flexibility to engage with the model beyond textual and regional prompts without modality45;specific designs. Through our proposed refocusing mechanism the generated grounding output is guided to better focus on the referenced object implicitly incorporating additional pixel45;level supervision. This simple modification utilizes attention scores generated during the inference of LLM eliminating the need for extra computations while exhibiting performance enhancements in both grounding masks and referring expressions. With only publicly available training data our model achieves state45;of45;the45;art results across multiple benchmarks including diverse modality referring segmentation and region45;level referring expression generation.
