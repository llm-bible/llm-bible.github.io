---
layout: publication
title: SciGraphQA A Large-Scale Synthetic Multi-Turn Question-Answering Dataset for Scientific Graphs
authors: Li Shengzhi, Tajbakhsh Nima
conference: "Arxiv"
year: 2023
bibkey: li2023scigraphqa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.03349"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG']
---
In this work we present SciGraphQA a synthetic multi-turn question-answer dataset related to academic graphs. SciGraphQA is 13 times larger than ChartVQA the previously largest chart-visual question-answering dataset. It is also the largest open-sourced chart VQA dataset with non-synthetic charts. To build our dataset we selected 290000 Computer Science or Machine Learning ArXiv papers published between 2010 and 2020 and then used Palm-2 to generate 295K samples of open-vocabulary multi-turn question-answering dialogues about the graphs. As context we provided the text-only Palm-2 with paper title abstract paragraph mentioning the graph and rich text contextual data from the graph itself obtaining dialogues with an average 2.23 question-answer turns for each graph. We asked GPT-4 to assess the matching quality of our question-answer turns given the papers context obtaining an average rating of 8.7/10 on our 3K test set. We evaluated the 0-shot capability of the most popular MLLM models such as LLaVa mPLUGowl BLIP-2 and openFlamingos on our dataset finding LLaVA-13B being the most performant with a CIDEr score of 0.08. We further enriched the question prompts for LLAVA by including the serialized data tables extracted from the graphs using the DePlot model boosting LLaVAs 0-shot CIDEr to 0.15. To verify the validity of our dataset we also fine-tuned LLaVa using our dataset reaching a substantially higher CIDEr score of 0.26. We anticipate further accuracy improvement by including segmentation mask tokens and leveraging larger LLM backbones coupled with emergent prompting techniques. Our code and data are open-sourced.
