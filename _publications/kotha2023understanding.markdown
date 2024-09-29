---
layout: publication
title: Understanding Catastrophic Forgetting In Language Models Via Implicit Inference
authors: Kotha Suhas, Springer Jacob Mitchell, Raghunathan Aditi
conference: "Arxiv"
year: 2023
bibkey: kotha2023understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10105"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
We lack a systematic understanding of the effects of fine45;tuning (via methods such as instruction45;tuning or reinforcement learning from human feedback) particularly on tasks outside the narrow fine45;tuning distribution. In a simplified scenario we demonstrate that improving performance on tasks within the fine45;tuning data distribution comes at the expense of capabilities on other tasks. We hypothesize that language models implicitly infer the task of the prompt and that fine45;tuning skews this inference towards tasks in the fine45;tuning distribution. To test this we propose Conjugate Prompting which artificially makes the task look farther from the fine45;tuning distribution while requiring the same capability and we find that this recovers some of the pretraining capabilities in our synthetic setup. Since real45;world fine45;tuning distributions are predominantly English we apply conjugate prompting to recover pretrained capabilities in LLMs by simply translating the prompts to different languages. This allows us to recover in45;context learning abilities lost via instruction tuning natural reasoning capability lost during code fine45;tuning and more concerningly harmful content generation suppressed by safety fine45;tuning in chatbots like ChatGPT.
