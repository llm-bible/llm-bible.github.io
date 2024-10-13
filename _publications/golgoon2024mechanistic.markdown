---
layout: publication
title: 'Mechanistic Interpretability Of Large Language Models With Applications To The Financial Services Industry'
authors: Golgoon Ashkan, Filom Khashayar, Kannan Arjun Ravi
conference: "Arxiv"
year: 2024
bibkey: golgoon2024mechanistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11215"}
tags: ['Applications', 'Attention Mechanism', 'Bias Mitigation', 'Ethics And Bias', 'Fairness', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Responsible AI', 'Transformer']
---
Large Language Models such as GPTs (Generative Pre-trained Transformers)
exhibit remarkable capabilities across a broad spectrum of applications.
Nevertheless, due to their intrinsic complexity, these models present
substantial challenges in interpreting their internal decision-making
processes. This lack of transparency poses critical challenges when it comes to
their adaptation by financial institutions, where concerns and accountability
regarding bias, fairness, and reliability are of paramount importance.
Mechanistic interpretability aims at reverse engineering complex AI models such
as transformers. In this paper, we are pioneering the use of mechanistic
interpretability to shed some light on the inner workings of large language
models for use in financial services applications. We offer several examples of
how algorithmic tasks can be designed for compliance monitoring purposes. In
particular, we investigate GPT-2 Small's attention pattern when prompted to
identify potential violation of Fair Lending laws. Using direct logit
attribution, we study the contributions of each layer and its corresponding
attention heads to the logit difference in the residual stream. Finally, we
design clean and corrupted prompts and use activation patching as a causal
intervention method to localize our task completion components further. We
observe that the (positive) heads \\(10.2\\) (head \\(2\\), layer \\(10\\)), \\(10.7\\), and
\\(11.3\\), as well as the (negative) heads \\(9.6\\) and \\(10.6\\) play a significant
role in the task completion.
