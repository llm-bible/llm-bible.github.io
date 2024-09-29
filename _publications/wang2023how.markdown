---
layout: publication
title: How Far Can Camels Go Exploring The State Of Instruction Tuning On Open Resources
authors: Wang Yizhong, Ivison Hamish, Dasigi Pradeep, Hessel Jack, Khot Tushar, Chandu Khyathi Raghavi, Wadden David, Macmillan Kelsey, Smith Noah A., Beltagy Iz, Hajishirzi Hannaneh
conference: "Arxiv"
year: 2023
bibkey: wang2023how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.04751"}
  - {name: "Code", url: "https://github.com/allenai/open&#45;instruct"}
tags: ['Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Tools']
---
In this work we explore recent advances in instruction45;tuning language models on a range of open instruction45;following datasets. Despite recent claims that open models can be on par with state45;of45;the45;art proprietary models these claims are often accompanied by limited evaluation making it difficult to compare models across the board and determine the utility of various resources. We provide a large set of instruction45;tuned models from 6.7B to 65B parameters in size trained on 12 instruction datasets ranging from manually curated (e.g. OpenAssistant) to synthetic and distilled (e.g. Alpaca) and systematically evaluate them on their factual knowledge reasoning multilinguality coding and open45;ended instruction following abilities through a collection of automatic model45;based and human45;based metrics. We further introduce Tulu our best performing instruction45;tuned model suite finetuned on a combination of high45;quality open resources. Our experiments show that different instruction45;tuning datasets can uncover or enhance specific skills while no single dataset (or combination) provides the best performance across all evaluations. Interestingly we find that model and human preference45;based evaluations fail to reflect differences in model capabilities exposed by benchmark45;based evaluations suggesting the need for the type of systemic evaluation performed in this work. Our evaluations show that the best model in any given evaluation reaches on average 8737; of ChatGPT performance and 7337; of GPT45;4 performance suggesting that further investment in building better base models and instruction45;tuning data is required to close the gap. We release our instruction45;tuned models including a fully finetuned 65B Tulu along with our code data and evaluation framework at https://github.com/allenai/open&#45;instruct to facilitate future research.
