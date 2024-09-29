---
layout: publication
title: 'Efficient And Effective Text Encoding For Chinese Llama And Alpaca'
authors: Cui Yiming, Yang Ziqing, Yao Xin
conference: "Arxiv"
year: 2023
bibkey: cui2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.08177"}
  - {name: "Code", url: "https://github.com/ymcui/Chinese-LLaMA-Alpaca"}
  - {name: "Code", url: "https://github.com/ymcui/Chinese-LLaMA-Alpaca-2"}
tags: ['Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'TACL', 'Training Techniques']
---
Large Language Models (LLMs) such as ChatGPT and GPT-4 have dramatically transformed natural language processing research and shown promising strides towards Artificial General Intelligence (AGI). Nonetheless the high costs associated with training and deploying LLMs present substantial obstacles to transparent accessible academic research. While several large language models such as LLaMA have been open-sourced by the community these predominantly focus on English corpora limiting their usefulness for other languages. In this paper we propose a method to augment LLaMA with capabilities for understanding and generating Chinese text and its ability to follow instructions. We achieve this by extending LLaMAs existing vocabulary with an additional 20000 Chinese tokens thereby improving its encoding efficiency and semantic understanding of Chinese. We further incorporate secondary pre-training using Chinese data and fine-tune the model with Chinese instruction datasets significantly enhancing the models ability to comprehend and execute instructions. Our experimental results indicate that the newly proposed model markedly enhances the original LLaMAs proficiency in understanding and generating Chinese content. Additionally the results on the C-Eval dataset yield competitive performance among the models with several times the size of ours. We have made our pre-trained models training scripts and other resources available through GitHub fostering open research for our community. Chinese LLaMA series (urlhttps://github.com/ymcui/Chinese-LLaMA-Alpaca\}\) and Chinese Llama-2 series (urlhttps://github.com/ymcui/Chinese-LLaMA-Alpaca-2\}\)"
