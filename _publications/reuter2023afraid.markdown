---
layout: publication
title: Im Afraid I Cant Do That Predicting Prompt Refusal In Black-box Generative Language Models
authors: Reuter Max, Schulze William
conference: "Arxiv"
year: 2023
bibkey: reuter2023afraid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.03423"}
  - {name: "Code", url: "https://github.com/maxwellreuter/chatgpt-refusals"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security', 'Training Techniques']
---
Since the release of OpenAIs ChatGPT generative language models have attracted extensive public attention. The increased usage has highlighted generative models broad utility but also revealed several forms of embedded bias. Some is induced by the pre-training corpus; but additional bias specific to generative models arises from the use of subjective fine-tuning to avoid generating harmful content. Fine-tuning bias may come from individual engineers and company policies and affects which prompts the model chooses to refuse. In this experiment we characterize ChatGPTs refusal behavior using a black-box attack. We first query ChatGPT with a variety of offensive and benign prompts (n=1706) then manually label each response as compliance or refusal. Manual examination of responses reveals that refusal is not cleanly binary and lies on a continuum; as such we map several different kinds of responses to a binary of compliance or refusal. The small manually-labeled dataset is used to train a refusal classifier which achieves an accuracy of 9637;. Second we use this refusal classifier to bootstrap a larger (n=10000) dataset adapted from the Quora Insincere Questions dataset. With this machine-labeled data we train a prompt classifier to predict whether ChatGPT will refuse a given question without seeing ChatGPTs response. This prompt classifier achieves 7637; accuracy on a test set of manually labeled questions (n=985). We examine our classifiers and the prompt n-grams that are most predictive of either compliance or refusal. Our datasets and code are available at https://github.com/maxwellreuter/chatgpt-refusals.
