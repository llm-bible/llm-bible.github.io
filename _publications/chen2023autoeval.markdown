---
layout: publication
title: Autoeval-video\: An Automatic Benchmark For Assessing Large Vision Language Models In Open-ended Video Question Answering
authors: Chen Xiuyuan, Lin Yuan, Zhang Yuchen, Huang Weiran
conference: "Arxiv"
year: 2023
bibkey: chen2023autoeval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.14906"}
  - {name: "Code", url: "https://github.com/Xiuyuan-Chen/AutoEval-Video"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Security']
---
We propose a novel and challenging benchmark AutoEval-Video to comprehensively evaluate large vision-language models in open-ended video question answering. The comprehensiveness of AutoEval-Video is demonstrated in two aspects 1) AutoEval-Video constructs open-ended video-questions across 9 skill dimensions addressing capabilities of perception comprehension and generation. 2) AutoEval-Video contains newly collected videos that cover over 40 distinct themes. To efficiently evaluate responses to the open-ended questions we employ an LLM-based evaluation approach but instead of merely providing a reference answer we annotate unique evaluation rules for every single instance (video-question pair). To maximize the robustness of these rules we develop a novel adversarial annotation mechanism. By using instance-specific rules as prompt GPT-4 as an automatic evaluator can achieve a stable evaluation accuracy of around 97.037; comparable to the 94.937; - 97.537; accuracy of a human evaluator. Furthermore we assess the performance of eight large vision-language models on AutoEval-Video. Among them GPT-4V(ision) significantly outperforms other models achieving an accuracy of 32.237;. However there is still substantial room for improvement compared to human accuracy of 72.837;. By conducting an extensive case study we uncover several drawbacks of GPT-4V such as limited temporal and dynamic comprehension and overly general responses. Code is available at https://github.com/Xiuyuan-Chen/AutoEval-Video."
