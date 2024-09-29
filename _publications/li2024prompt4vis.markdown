---
layout: publication
title: Prompt4vis Prompting Large Language Models With Example Mining And Schema Filtering For Tabular Data Visualization
authors: Li Shuaimin, Chen Xuanang, Song Yuanfeng, Song Yunze, Zhang Chen
conference: "Arxiv"
year: 2024
bibkey: li2024prompt4vis
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.07909"}
tags: ['Attention Mechanism', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
Data visualization (DV) systems are increasingly recognized for their profound capability to uncover insights from vast datasets gaining attention across both industry and academia. Crafting data queries is an essential process within certain declarative visualization languages (DVLs e.g. Vega-Lite EChart.). The evolution of natural language processing (NLP) technologies has streamlined the use of natural language interfaces to visualize tabular data offering a more accessible and intuitive user experience. However current methods for converting natural language questions into data visualization queries such as Seq2Vis ncNet and RGVisNet despite utilizing complex neural network architectures still fall short of expectations and have great room for improvement. Large language models (LLMs) such as ChatGPT and GPT-4 have established new benchmarks in a variety of NLP tasks fundamentally altering the landscape of the field. Inspired by these advancements we introduce a novel framework Prompt4Vis leveraging LLMs and in-context learning to enhance the performance of generating data visualization from natural language. Prompt4Vis comprises two key components (1) a multi-objective example mining module designed to find out the truly effective examples that strengthen the LLMs in-context learning capabilities for text-to-vis; (2) a schema filtering module which is proposed to simplify the schema of the database. Extensive experiments through 5-fold cross-validation on the NVBench dataset demonstrate the superiority of Prompt4Vis which notably surpasses the state-of-the-art (SOTA) RGVisNet by approximately 35.937; and 71.337; on dev and test sets respectively. To the best of our knowledge Prompt4Vis is the first work that introduces in-context learning into the text-to-vis for generating data visualization queries.
