---
layout: publication
title: 'Fine-tuning Large Language Models For Stock Return Prediction Using Newsflow'
authors: Guo Tian, Hauptmann Emmanuel
conference: "Arxiv"
year: 2024
bibkey: guo2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.18103"}
tags: ['BERT', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
'Large language models (LLMs) and their fine-tuning techniques have demonstrated superior performance in various language understanding and generation tasks. This paper explores fine-tuning LLMs for stock return forecasting with financial newsflow. In quantitative investing, return forecasting is fundamental for subsequent tasks like stock picking, portfolio optimization, etc. We formulate the model to include text representation and forecasting modules. We propose to compare the encoder-only and decoder-only LLMs, considering they generate text representations in distinct ways. The impact of these different representations on forecasting performance remains an open question. Meanwhile, we compare two simple methods of integrating LLMs'' token-level representations into the forecasting module. The experiments on real news and investment universes reveal that: (1) aggregated representations from LLMs'' token-level embeddings generally produce return predictions that enhance the performance of long-only and long-short portfolios; (2) in the relatively large investment universe, the decoder LLMs-based prediction model leads to stronger portfolios, whereas in the small universes, there are no consistent winners. Among the three LLMs studied (DeBERTa, Mistral, Llama), Mistral performs more robustly across different universes; (3) return predictions derived from LLMs'' text representations are a strong signal for portfolio construction, outperforming conventional sentiment scores.'
