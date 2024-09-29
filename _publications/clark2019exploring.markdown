---
layout: publication
title: Boolq Exploring The Surprising Difficulty Of Natural Yes/no Questions
authors: Clark Christopher, Lee Kenton, Chang Ming-wei, Kwiatkowski Tom, Collins Michael, Toutanova Kristina
conference: "Arxiv"
year: 2019
bibkey: clark2019exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1905.10044"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Prompting']
---
In this paper we study yes/no questions that are naturally occurring 45;45;45; meaning that they are generated in unprompted and unconstrained settings. We build a reading comprehension dataset BoolQ of such questions and show that they are unexpectedly challenging. They often query for complex non45;factoid information and require difficult entailment45;like inference to solve. We also explore the effectiveness of a range of transfer learning baselines. We find that transferring from entailment data is more effective than transferring from paraphrase or extractive QA data and that it surprisingly continues to be very beneficial even when starting from massive pre45;trained language models such as BERT. Our best method trains BERT on MultiNLI and then re45;trains it on our train set. It achieves 80.437; accuracy compared to 9037; accuracy of human annotators (and 6237; majority45;baseline) leaving a significant gap for future work.
