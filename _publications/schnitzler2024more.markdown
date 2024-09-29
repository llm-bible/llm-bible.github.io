---
layout: publication
title: Morehopqa More Than Multi45;hop Reasoning
authors: Schnitzler Julian, Ho Xanh, Huang Jiahao, Boudin Florian, Sugawara Saku, Aizawa Akiko
conference: "Arxiv"
year: 2024
bibkey: schnitzler2024more
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13397"}
  - {name: "Code", url: "https://github.com/Alab&#45;NII/morehopqa"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture']
---
Most existing multi45;hop datasets are extractive answer datasets where the answers to the questions can be extracted directly from the provided context. This often leads models to use heuristics or shortcuts instead of performing true multi45;hop reasoning. In this paper we propose a new multi45;hop dataset MoreHopQA which shifts from extractive to generative answers. Our dataset is created by utilizing three existing multi45;hop datasets HotpotQA 2WikiMultihopQA and MuSiQue. Instead of relying solely on factual reasoning we enhance the existing multi45;hop questions by adding another layer of questioning that involves one two or all three of the following types of reasoning commonsense arithmetic and symbolic. Our dataset is created through a semi45;automated process resulting in a dataset with 1118 samples that have undergone human verification. We then use our dataset to evaluate five different large language models Mistral 7B Gemma 7B Llama 3 (8B and 70B) and GPT45;4. We also design various cases to analyze the reasoning steps in the question45;answering process. Our results show that models perform well on initial multi45;hop questions but struggle with our extended questions indicating that our dataset is more challenging than previous ones. Our analysis of question decomposition reveals that although models can correctly answer questions only a portion 45; 38.737; for GPT45;4 and 33.437; for Llama345;70B 45; achieve perfect reasoning where all corresponding sub45;questions are answered correctly. Evaluation code and data are available at https://github.com/Alab&#45;NII/morehopqa
