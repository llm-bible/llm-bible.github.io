---
layout: publication
title: Can Llms Express Their Uncertainty An Empirical Evaluation Of Confidence Elicitation In Llms
authors: Xiong Miao, Hu Zhiyuan, Lu Xinyang, Li Yifei, Fu Jie, He Junxian, Hooi Bryan
conference: "Arxiv"
year: 2023
bibkey: xiong2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.13063"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'Tools']
---
Empowering large language models to accurately express confidence in their answers is essential for trustworthy decision45;making. Previous confidence elicitation methods which primarily rely on white45;box access to internal model information or model fine45;tuning have become less suitable for LLMs especially closed45;source commercial APIs. This leads to a growing need to explore the untapped area of black45;box approaches for LLM uncertainty estimation. To better break down the problem we define a systematic framework with three components prompting strategies for eliciting verbalized confidence sampling methods for generating multiple responses and aggregation techniques for computing consistency. We then benchmark these methods on two key tasks45;confidence calibration and failure prediction45;across five types of datasets (e.g. commonsense and arithmetic reasoning) and five widely45;used LLMs including GPT45;4 and LLaMA 2 Chat. Our analysis uncovers several key insights 1) LLMs when verbalizing their confidence tend to be overconfident potentially imitating human patterns of expressing confidence. 2) As model capability scales up both calibration and failure prediction performance improve. 3) Employing our proposed strategies such as human45;inspired prompts consistency among multiple responses and better aggregation strategies can help mitigate this overconfidence from various perspectives. 4) Comparisons with white45;box methods indicate that while white45;box methods perform better the gap is narrow e.g. 0.522 to 0.605 in AUROC. Despite these advancements none of these techniques consistently outperform others and all investigated methods struggle in challenging tasks such as those requiring professional knowledge indicating significant scope for improvement. We believe this study can serve as a strong baseline and provide insights for eliciting confidence in black45;box LLMs.
