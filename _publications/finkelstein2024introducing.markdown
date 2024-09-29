---
layout: publication
title: Introducing The Newspalm MBR And QE Dataset&#58; Llm-generated High-quality Parallel Data Outperforms Traditional Web-crawled Data
authors: Finkelstein Mara, Vilar David, Freitag Markus
conference: "Arxiv"
year: 2024
bibkey: finkelstein2024introducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06537"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Few Shot', 'Training Techniques']
---
Recent research in neural machine translation (NMT) has shown that training on high-quality machine-generated data can outperform training on human-generated data. This work accompanies the first-ever release of a LLM-generated MBR-decoded and QE-reranked dataset with both sentence-level and multi-sentence examples. We perform extensive experiments to demonstrate the quality of our dataset in terms of its downstream impact on NMT model performance. We find that training from scratch on our (machine-generated) dataset outperforms training on the (web-crawled) WMT23 training dataset (which is 300 times larger) and also outperforms training on the top-quality subset of the WMT23 training dataset. We also find that performing self-distillation by finetuning the LLM which generated this dataset outperforms the LLMs strong few-shot baseline. These findings corroborate the quality of our dataset and demonstrate the value of high-quality machine-generated data in improving performance of NMT models.
