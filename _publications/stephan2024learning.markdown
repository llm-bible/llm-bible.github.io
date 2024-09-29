---
layout: publication
title: RLVF Learning From Verbal Feedback Without Overgeneralization
authors: Stephan Moritz, Khazatsky Alexander, Mitchell Eric, Chen Annie S, Hsu Sheryl, Sharma Archit, Finn Chelsea
conference: "Arxiv"
year: 2024
bibkey: stephan2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10893"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
The diversity of contexts in which large language models (LLMs) are deployed requires the ability to modify or customize default model behaviors to incorporate nuanced requirements and preferences. A convenient interface to specify such model adjustments is high45;level verbal feedback such as Dont use emojis when drafting emails to my boss. However while writing high45;level feedback is far simpler than collecting annotations for reinforcement learning from human feedback (RLHF) we find that simply prompting a model with such feedback leads to overgeneralization of the feedback to contexts where it is not relevant. We study the problem of incorporating verbal feedback without such overgeneralization inspiring a new method Contextualized Critiques with Constrained Preference Optimization (C3PO). C3PO uses a piece of high45;level feedback to generate a small synthetic preference dataset specifying how the feedback should (and should not) be applied. It then fine45;tunes the model in accordance with the synthetic preference data while minimizing the divergence from the original model for prompts where the feedback does not apply. Our experimental results indicate that our approach effectively applies verbal feedback to relevant scenarios while preserving existing behaviors for other contexts. For both human45; and GPT45;445;generated high45;level feedback C3PO effectively adheres to the given feedback comparably to in45;context baselines while reducing overgeneralization by 3037;.
