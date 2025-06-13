---
layout: publication
title: 'HRLAIF: Improvements In Helpfulness And Harmlessness In Open-domain Reinforcement Learning From AI Feedback'
authors: Ang Li, Qiugen Xiao, Peng Cao, Jian Tang, Yi Yuan, Zijie Zhao, Xiaoyuan Chen, Liang Zhang, Xiangyang Li, Kaitong Yang, Weidong Guo, Yukang Gan, Xu Yu, Daniell Wang, Ying Shan
conference: "Arxiv"
year: 2024
bibkey: li2024improvements
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.08309"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting']
---
Reinforcement Learning from AI Feedback (RLAIF) has the advantages of shorter
annotation cycles and lower costs over Reinforcement Learning from Human
Feedback (RLHF), making it highly efficient during the rapid strategy iteration
periods of large language model (LLM) training. Using ChatGPT as a labeler to
provide feedback on open-domain prompts in RLAIF training, we observe an
increase in human evaluators' preference win ratio for model responses, but a
decrease in evaluators' satisfaction rate. Analysis suggests that the decrease
in satisfaction rate is mainly due to some responses becoming less helpful,
particularly in terms of correctness and truthfulness, highlighting practical
limitations of basic RLAIF. In this paper, we propose Hybrid Reinforcement
Learning from AI Feedback (HRLAIF). This method enhances the accuracy of AI
annotations for responses, making the model's helpfulness more robust in
training process. Additionally, it employs AI for Red Teaming, further
improving the model's harmlessness. Human evaluation results show that HRLAIF
inherits the ability of RLAIF to enhance human preference for outcomes at a low
cost while also improving the satisfaction rate of responses. Compared to the
policy model before Reinforcement Learning (RL), it achieves an increase of
2.08% in satisfaction rate, effectively addressing the issue of a decrease of
4.58% in satisfaction rate after basic RLAIF.
