---
layout: publication
title: Eagle Ethical Dataset Given from Real Interactions
authors: Kaneko Masahiro, Bollegala Danushka, Baldwin Timothy
conference: "Arxiv"
year: 2024
bibkey: kaneko2024eagle
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14258"}
  - {name: "Code", url: "https://huggingface.co/datasets/MasahiroKaneko/eagle"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Recent studies have demonstrated that large language models (LLMs) have ethical-related problems such as social biases lack of moral reasoning and generation of offensive content. The existing evaluation metrics and methods to address these ethical challenges use datasets intentionally created by instructing humans to create instances including ethical problems. Therefore the data does not reflect prompts that users actually provide when utilizing LLM services in everyday contexts. This may not lead to the development of safe LLMs that can address ethical challenges arising in real-world applications. In this paper we create Eagle datasets extracted from real interactions between ChatGPT and users that exhibit social biases toxicity and immoral problems. Our experiments show that Eagle captures complementary aspects not covered by existing datasets proposed for evaluation and mitigation of such ethical challenges. Our code is publicly available at https://huggingface.co/datasets/MasahiroKaneko/eagle.
