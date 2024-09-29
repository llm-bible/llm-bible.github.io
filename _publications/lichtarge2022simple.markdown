---
layout: publication
title: Simple And Effective Gradient45;based Tuning Of Sequence45;to45;sequence Models
authors: Lichtarge Jared, Alberti Chris, Kumar Shankar
conference: "Arxiv"
year: 2022
bibkey: lichtarge2022simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.04683"}
tags: ['Applications', 'Efficiency And Optimization', 'Ethics And Bias', 'Pretraining Methods', 'Training Techniques']
---
Recent trends towards training ever45;larger language models have substantially improved machine learning performance across linguistic tasks. However the huge cost of training larger models can make tuning them prohibitively expensive motivating the study of more efficient methods. Gradient45;based hyper45;parameter optimization offers the capacity to tune hyper45;parameters during training yet has not previously been studied in a sequence45;to45;sequence setting. We apply a simple and general gradient45;based hyperparameter optimization method to sequence45;to45;sequence tasks for the first time demonstrating both efficiency and performance gains over strong baselines for both Neural Machine Translation and Natural Language Understanding (NLU) tasks (via T5 pretraining). For translation we show the method generalizes across language pairs is more efficient than Bayesian hyper45;parameter optimization and that learned schedules for some hyper45;parameters can out45;perform even optimal constant45;valued tuning. For T5 we show that learning hyper45;parameters during pretraining can improve performance across downstream NLU tasks. When learning multiple hyper45;parameters concurrently we show that the global learning rate can follow a schedule over training that improves performance and is not explainable by the short45;horizon bias of greedy methods citep123;wu2018125;. We release the code used to facilitate further research.
