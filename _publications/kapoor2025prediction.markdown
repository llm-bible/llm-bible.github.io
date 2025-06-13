---
layout: publication
title: 'Prediction Of Item Difficulty For Reading Comprehension Items By Creation Of Annotated Item Repository'
authors: Radhika Kapoor, Sang T. Truong, Nick Haber, Maria Araceli Ruiz-primo, Benjamin W. Domingue
conference: "Arxiv"
year: 2025
bibkey: kapoor2025prediction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20663"}
tags: ['BERT', 'Model Architecture']
---
Prediction of item difficulty based on its text content is of substantial
interest. In this paper, we focus on the related problem of recovering
IRT-based difficulty when the data originally reported item p-value (percent
correct responses). We model this item difficulty using a repository of reading
passages and student data from US standardized tests from New York and Texas
for grades 3-8 spanning the years 2017-23. This repository is annotated with
meta-data on (1) linguistic features of the reading items, (2) test features of
the passage, and (3) context features. A penalized regression prediction model
with all these features can predict item difficulty with RMSE 0.52 compared to
baseline RMSE of 0.92, and with a correlation of 0.77 between true and
predicted difficulty. We supplement these features with embeddings from LLMs
(ModernBERT, BERT, and LlAMA), which marginally improve item difficulty
prediction. When models use only item linguistic features or LLM embeddings,
prediction performance is similar, which suggests that only one of these
feature categories may be required. This item difficulty prediction model can
be used to filter and categorize reading items and will be made publicly
available for use by other stakeholders.
