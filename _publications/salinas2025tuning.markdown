---
layout: publication
title: 'Tuning LLM Judge Design Decisions For 1/1000 Of The Cost'
authors: David Salinas, Omar Swelam, Frank Hutter
conference: "Arxiv"
year: 2025
bibkey: salinas2025tuning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.17178'}
  - {name: "Code", url: 'https://github.com/geoalgo/judgetuning'}
tags: ['RAG', 'Has Code', 'Efficiency and Optimization', 'Prompting']
---
Evaluating Large Language Models (LLMs) often requires costly human annotations. To address this, LLM-based judges have been proposed, which compare the outputs of two LLMs enabling the ranking of models without human intervention. While several approaches have been proposed, many confounding factors are present between different papers. For instance the model, the prompt and other hyperparameters are typically changed at the same time making apple-to-apple comparisons challenging. In this paper, we propose to systematically analyze and tune the hyperparameters of LLM judges. To alleviate the high cost of evaluating a judge, we propose to leverage multi-objective multi-fidelity which allows to find judges that trade accuracy for cost and also significantly reduce the cost of the search. Our method identifies judges that not only outperform existing benchmarks in accuracy and cost-efficiency but also utilize open-weight models, ensuring greater accessibility and reproducibility. The code to reproduce our experiments is available at this repository https://github.com/geoalgo/judgetuning .
