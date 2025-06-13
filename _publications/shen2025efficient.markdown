---
layout: publication
title: 'Efficient Jailbreaking Of Large Models By Freeze Training: Lower Layers Exhibit Greater Sensitivity To Harmful Content'
authors: Hongyuan Shen, Min Zheng, Jincheng Wang, Yang Zhao
conference: "Arxiv"
year: 2025
bibkey: shen2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20952"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability', 'Attention Mechanism']
---
With the widespread application of Large Language Models across various
domains, their security issues have increasingly garnered significant attention
from both academic and industrial communities. This study conducts sampling and
normalization of the parameters of the LLM to generate visual representations
and heatmaps of parameter distributions, revealing notable discrepancies in
parameter distributions among certain layers within the hidden layers. Further
analysis involves calculating statistical metrics for each layer, followed by
the computation of a Comprehensive Sensitivity Score based on these metrics,
which identifies the lower layers as being particularly sensitive to the
generation of harmful content. Based on this finding, we employ a Freeze
training strategy, selectively performing Supervised Fine-Tuning only on the
lower layers. Experimental results demonstrate that this method significantly
reduces training duration and GPU memory consumption while maintaining a high
jailbreak success rate and a high harm score, outperforming the results
achieved by applying the LoRA method for SFT across all layers. Additionally,
the method has been successfully extended to other open-source large models,
validating its generality and effectiveness across different model
architectures. Furthermore, we compare our method with ohter jailbreak method,
demonstrating the superior performance of our approach. By innovatively
proposing a method to statistically analyze and compare large model parameters
layer by layer, this study provides new insights into the interpretability of
large models. These discoveries emphasize the necessity of continuous research
and the implementation of adaptive security measures in the rapidly evolving
field of LLMs to prevent potential jailbreak attack risks, thereby promoting
the development of more robust and secure LLMs.
