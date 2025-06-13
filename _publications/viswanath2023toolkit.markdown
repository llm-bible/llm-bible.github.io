---
layout: publication
title: 'Fairpy: A Toolkit For Evaluation Of Prediction Biases And Their Mitigation In Large Language Models'
authors: Hrishikesh Viswanath, Tianyi Zhang
conference: "Arxiv"
year: 2023
bibkey: viswanath2023toolkit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.05508"}
  - {name: "Code", url: "https://github.com/HrishikeshVish/Fairpy}{https://github.com/HrishikeshVish/Fairpy"}
tags: ['Tools', 'GPT', 'Survey Paper', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'BERT']
---
Recent studies have demonstrated that large pretrained language models (LLMs)
such as BERT and GPT-2 exhibit biases in token prediction, often inherited from
the data distributions present in their training corpora. In response, a number
of mathematical frameworks have been proposed to quantify, identify, and
mitigate these the likelihood of biased token predictions. In this paper, we
present a comprehensive survey of such techniques tailored towards widely used
LLMs such as BERT, GPT-2, etc. We additionally introduce Fairpy, a modular and
extensible toolkit that provides plug-and-play interfaces for integrating these
mathematical tools, enabling users to evaluate both pretrained and custom
language models. Fairpy supports the implementation of existing debiasing
algorithms. The toolkit is open-source and publicly available at:
\href\{https://github.com/HrishikeshVish/Fairpy\}\{https://github.com/HrishikeshVish/Fairpy\}
