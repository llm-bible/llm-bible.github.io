---
layout: publication
title: 'Uicoder: Finetuning Large Language Models To Generate User Interface Code Through Automated Feedback'
authors: Wu Jason, Schoop Eldon, Leung Alan, Barik Titus, Bigham Jeffrey P., Nichols Jeffrey
conference: "Arxiv"
year: 2024
bibkey: wu2024finetuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07739"}
tags: ['Pretraining Methods', 'Tools']
---
Large language models (LLMs) struggle to consistently generate UI code that compiles and produces visually relevant designs. Existing approaches to improve generation rely on expensive human feedback or distilling a proprietary model. In this paper we explore the use of automated feedback (compilers and multi-modal models) to guide LLMs to generate high-quality UI code. Our method starts with an existing LLM and iteratively produces improved models by self-generating a large synthetic dataset using an original model applying automated tools to aggressively filter score and de-duplicate the data into a refined higher quality dataset. The original LLM is improved by finetuning on this refined dataset. We applied our approach to several open-source LLMs and compared the resulting performance to baseline models with both automated metrics and human preferences. Our evaluation shows the resulting models outperform all other downloadable baselines and approach the performance of larger proprietary models.
