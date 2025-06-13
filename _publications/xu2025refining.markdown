---
layout: publication
title: 'Refining Positive And Toxic Samples For Dual Safety Self-alignment Of Llms With Minimal Human Interventions'
authors: Jingxin Xu, Guoshun Nan, Sheng Guan, Sicong Leng, Yilian Liu, Zixiao Wang, Yuyang Ma, Zhili Zhou, Yanzhao Hou, Xiaofeng Tao
conference: "Arxiv"
year: 2025
bibkey: xu2025refining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08657"}
tags: ['Responsible AI', 'Agentic', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Recent AI agents, such as ChatGPT and LLaMA, primarily rely on instruction
tuning and reinforcement learning to calibrate the output of large language
models (LLMs) with human intentions, ensuring the outputs are harmless and
helpful. Existing methods heavily depend on the manual annotation of
high-quality positive samples, while contending with issues such as noisy
labels and minimal distinctions between preferred and dispreferred response
data. However, readily available toxic samples with clear safety distinctions
are often filtered out, removing valuable negative references that could aid
LLMs in safety alignment. In response, we propose PT-ALIGN, a novel safety
self-alignment approach that minimizes human supervision by automatically
refining positive and toxic samples and performing fine-grained dual
instruction tuning. Positive samples are harmless responses, while toxic
samples deliberately contain extremely harmful content, serving as a new
supervisory signals. Specifically, we utilize LLM itself to iteratively
generate and refine training instances by only exploring fewer than 50 human
annotations. We then employ two losses, i.e., maximum likelihood estimation
(MLE) and fine-grained unlikelihood training (UT), to jointly learn to enhance
the LLM's safety. The MLE loss encourages an LLM to maximize the generation of
harmless content based on positive samples. Conversely, the fine-grained UT
loss guides the LLM to minimize the output of harmful words based on negative
samples at the token-level, thereby guiding the model to decouple safety from
effectiveness, directing it toward safer fine-tuning objectives, and increasing
the likelihood of generating helpful and reliable content. Experiments on 9
popular open-source LLMs demonstrate the effectiveness of our PT-ALIGN for
safety alignment, while maintaining comparable levels of helpfulness and
usefulness.
