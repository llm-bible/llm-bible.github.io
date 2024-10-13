---
layout: publication
title: 'Evaluating Human Alignment And Model Faithfulness Of LLM Rationale'
authors: Fayyaz Mohsen, Yin Fan, Sun Jiao, Peng Nanyun
conference: "Arxiv"
year: 2024
bibkey: fayyaz2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00219"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
We study how well large language models (LLMs) explain their generations with
rationales -- a set of tokens extracted from the input texts that reflect the
decision process of LLMs. We examine LLM rationales extracted with two methods:
1) attribution-based methods that use attention or gradients to locate
important tokens, and 2) prompting-based methods that guide LLMs to extract
rationales using prompts. Through extensive experiments, we show that
prompting-based rationales align better with human-annotated rationales than
attribution-based rationales, and demonstrate reasonable alignment with humans
even when model performance is poor. We additionally find that the faithfulness
limitations of prompting-based methods, which are identified in previous work,
may be linked to their collapsed predictions. By fine-tuning these models on
the corresponding datasets, both prompting and attribution methods demonstrate
improved faithfulness. Our study sheds light on more rigorous and fair
evaluations of LLM rationales, especially for prompting-based ones.
