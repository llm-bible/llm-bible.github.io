---
layout: publication
title: 'Explaining Black Box Text Modules In Natural Language With Language Models'
authors: Singh Chandan, Hsu Aliyah R., Antonello Richard, Jain Shailee, Huth Alexander G., Yu Bin, Gao Jianfeng
conference: "Arxiv"
year: 2023
bibkey: singh2023explaining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.09863"}
tags: ['Applications', 'BERT', 'Interpretability And Explainability', 'Model Architecture', 'Tools', 'Uncategorized']
---
Large language models (LLMs) have demonstrated remarkable prediction performance for a growing array of tasks. However, their rapid proliferation and increasing opaqueness have created a growing need for interpretability. Here, we ask whether we can automatically obtain natural language explanations for black box text modules. A text module is any function that maps text to a scalar continuous value, such as a submodule within an LLM or a fitted model of a brain region. Black box indicates that we only have access to the module's inputs/outputs. We introduce Summarize and Score (SASC), a method that takes in a text module and returns a natural language explanation of the module's selectivity along with a score for how reliable the explanation is. We study SASC in 3 contexts. First, we evaluate SASC on synthetic modules and find that it often recovers ground truth explanations. Second, we use SASC to explain modules found within a pre-trained BERT model, enabling inspection of the model's internals. Finally, we show that SASC can generate explanations for the response of individual fMRI voxels to language stimuli, with potential applications to fine-grained brain mapping. All code for using SASC and reproducing results is made available on Github.
