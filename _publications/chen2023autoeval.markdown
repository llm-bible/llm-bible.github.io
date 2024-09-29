---
layout: publication
title: Autoeval45;video An Automatic Benchmark For Assessing Large Vision Language Models In Open45;ended Video Question Answering
authors: Chen Xiuyuan, Lin Yuan, Zhang Yuchen, Huang Weiran
conference: "Arxiv"
year: 2023
bibkey: chen2023autoeval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.14906"}
  - {name: "Code", url: "https://github.com/Xiuyuan&#45;Chen/AutoEval&#45;Video"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security']
---
We propose a novel and challenging benchmark AutoEval45;Video to comprehensively evaluate large vision45;language models in open45;ended video question answering. The comprehensiveness of AutoEval45;Video is demonstrated in two aspects 1) AutoEval45;Video constructs open45;ended video45;questions across 9 skill dimensions addressing capabilities of perception comprehension and generation. 2) AutoEval45;Video contains newly collected videos that cover over 40 distinct themes. To efficiently evaluate responses to the open45;ended questions we employ an LLM45;based evaluation approach but instead of merely providing a reference answer we annotate unique evaluation rules for every single instance (video45;question pair). To maximize the robustness of these rules we develop a novel adversarial annotation mechanism. By using instance45;specific rules as prompt GPT45;4 as an automatic evaluator can achieve a stable evaluation accuracy of around 97.037; comparable to the 94.937; 45; 97.537; accuracy of a human evaluator. Furthermore we assess the performance of eight large vision45;language models on AutoEval45;Video. Among them GPT45;4V(ision) significantly outperforms other models achieving an accuracy of 32.237;. However there is still substantial room for improvement compared to human accuracy of 72.837;. By conducting an extensive case study we uncover several drawbacks of GPT45;4V such as limited temporal and dynamic comprehension and overly general responses. Code is available at https://github.com/Xiuyuan&#45;Chen/AutoEval&#45;Video.
