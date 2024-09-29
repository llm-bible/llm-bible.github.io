---
layout: publication
title: Training45;free Long45;context Scaling Of Large Language Models
authors: An Chenxin, Huang Fei, Zhang Jun, Gong Shansan, Qiu Xipeng, Zhou Chang, Kong Lingpeng
conference: "Arxiv"
year: 2024
bibkey: an2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17463"}
  - {name: "Code", url: "https://github.com/HKUNLP/ChunkLlama&#125;"}
tags: ['Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
The ability of Large Language Models (LLMs) to process and generate coherent text is markedly weakened when the number of input tokens exceeds their pretraining length. Given the expensive overhead of finetuning large45;scale models with longer sequences we propose Dual Chunk Attention (DCA) which enables Llama2 70B to support context windows of more than 100k tokens without continual training. By decomposing the attention computation for long sequences into chunk45;based modules DCA manages to effectively capture the relative positional information of tokens within the same chunk (Intra45;Chunk) and across distinct chunks (Inter45;Chunk) as well as integrates seamlessly with Flash Attention. In addition to its impressive extrapolation capability DCA achieves performance on practical long45;context tasks that is comparable to or even better than that of finetuned models. When compared with proprietary models our training45;free 70B model attains 9437; of the performance of gpt45;3.545;16k indicating it is a viable open45;source alternative. All code and data used in this work are released at url123;https://github.com/HKUNLP/ChunkLlama&#125;.
