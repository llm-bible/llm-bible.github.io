---
layout: publication
title: Mumath45;code Combining Tool45;use Large Language Models With Multi45;perspective Data Augmentation For Mathematical Reasoning
authors: Yin Shuo, You Weihao, Ji Zhilong, Zhong Guoqiang, Bai Jinfeng
conference: "Arxiv"
year: 2024
bibkey: yin2024mumath
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07551"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques']
---
The tool45;use Large Language Models (LLMs) that integrate with external Python interpreters have significantly enhanced mathematical reasoning capabilities for open45;source LLMs while tool45;free methods chose another track augmenting math reasoning data. However a great method to integrate the above two research paths and combine their advantages remains to be explored. In this work we firstly include new math questions via multi45;perspective data augmenting methods and then synthesize code45;nested solutions to them. The open LLMs (i.e. Llama45;2) are finetuned on the augmented dataset to get the resulting models MuMath45;Code (μ45;Math45;Code). During the inference phase our MuMath45;Code generates code and interacts with the external python interpreter to get the execution results. Therefore MuMath45;Code leverages the advantages of both the external tool and data augmentation. To fully leverage the advantages of our augmented data we propose a two45;stage training strategy In Stage45;1 we finetune Llama45;2 on pure CoT data to get an intermediate model which then is trained on the code45;nested data in Stage45;2 to get the resulting MuMath45;Code. Our MuMath45;Code45;7B achieves 83.8 on GSM8K and 52.4 on MATH while MuMath45;Code45;70B model achieves new state45;of45;the45;art performance among open methods 45;45; achieving 90.737; on GSM8K and 55.137; on MATH. Extensive experiments validate the combination of tool use and data augmentation as well as our two45;stage training strategy. We release the proposed dataset along with the associated code for public use.
