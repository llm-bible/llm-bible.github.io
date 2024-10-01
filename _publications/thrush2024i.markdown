---
layout: publication
title: 'I Am A Strange Dataset: Metalinguistic Tests For Language Models'
authors: Thrush Tristan, Moore Jared, Monares Miguel, Potts Christopher, Kiela Douwe
conference: "Arxiv"
year: 2024
bibkey: thrush2024i
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05300"}
  - {name: "Code", url: "https://github.com/TristanThrush/i-am-a-strange-dataset"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
'Statements involving metalinguistic self-reference (This paper has six sections.) are prevalent in many domains. Can current large language models (LLMs) handle such language? In this paper, we present I am a Strange Dataset, a new dataset for addressing this question. There are two subtasks: generation and verification. In generation, models continue statements like The penultimate word in this sentence is (where a correct continuation is is). In verification, models judge the truth of statements like The penultimate word in this sentence is sentence. (false). We also provide minimally different metalinguistic non-self-reference examples to complement the main dataset by probing for whether models can handle metalinguistic language at all. The dataset is hand-crafted by experts and validated by non-expert annotators. We test a variety of open-source LLMs (7B to 70B parameters) as well as closed-source LLMs through APIs. All models perform close to chance across both subtasks and even on the non-self-referential metalinguistic control data, though we find some steady improvement with model scale. GPT 4 is the only model to consistently do significantly better than chance, and it is still only in the 60&#37; range, while our untrained human annotators score well in the 89-93&#37; range. The dataset and evaluation toolkit are available at https://github.com/TristanThrush/i-am-a-strange-dataset.'
