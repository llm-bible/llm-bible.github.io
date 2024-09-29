---
layout: publication
title: Prompt45;based Bias Calibration For Better Zero/few45;shot Learning Of Language Models
authors: He Kang, Long Yinghan, Roy Kaushik
conference: "Arxiv"
year: 2024
bibkey: he2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10353"}
tags: ['Bias Mitigation', 'Efficiency And Optimization', 'Ethics And Bias', 'Fairness', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting', 'RAG']
---
Prompt learning is susceptible to intrinsic bias present in pre45;trained language models (LMs) resulting in sub45;optimal performance of prompt45;based zero/few45;shot learning. In this work we propose a null45;input prompting method to calibrate intrinsic bias encoded in pre45;trained LMs. Different from prior efforts that address intrinsic bias primarily for social fairness and often involve excessive computational cost our objective is to explore enhancing LMs performance in downstream zero/few45;shot learning while emphasizing the efficiency of intrinsic bias calibration. Specifically we leverage a diverse set of auto45;selected null45;meaning inputs generated from GPT45;4 to prompt pre45;trained LMs for intrinsic bias probing. Utilizing the bias45;reflected probability distribution we formulate a distribution disparity loss for bias calibration where we exclusively update bias parameters (0.137; of total parameters) of LMs towards equal probability distribution. Experimental results show that the calibration promotes an equitable starting point for LMs while preserving language modeling abilities. Across a wide range of datasets including sentiment analysis and topic classification our method significantly improves zero/few45;shot learning performance of LMs for both in45;context learning and prompt45;based fine45;tuning (on average 937; and 237; respectively).
