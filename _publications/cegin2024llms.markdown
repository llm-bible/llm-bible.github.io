---
layout: publication
title: 'Llms Vs Established Text Augmentation Techniques For Classification: When Do The Benefits Outweight The Costs?'
authors: Jan Cegin, Jakub Simko, Peter Brusilovsky
conference: "Arxiv"
year: 2024
bibkey: cegin2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16502"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
The generative large language models (LLMs) are increasingly being used for
data augmentation tasks, where text samples are LLM-paraphrased and then used
for classifier fine-tuning. However, a research that would confirm a clear
cost-benefit advantage of LLMs over more established augmentation methods is
largely missing. To study if (and when) is the LLM-based augmentation
advantageous, we compared the effects of recent LLM augmentation methods with
established ones on 6 datasets, 3 classifiers and 2 fine-tuning methods. We
also varied the number of seeds and collected samples to better explore the
downstream model accuracy space. Finally, we performed a cost-benefit analysis
and show that LLM-based methods are worthy of deployment only when very small
number of seeds is used. Moreover, in many cases, established methods lead to
similar or better model accuracies.
