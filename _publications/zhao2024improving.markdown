---
layout: publication
title: Improving The Robustness Of Large Language Models Via Consistency Alignment
authors: Zhao Yukun, Yan Lingyong, Sun Weiwei, Xing Guoliang, Wang Shuaiqiang, Meng Chong, Cheng Zhicong, Ren Zhaochun, Yin Dawei
conference: "Arxiv"
year: 2024
bibkey: zhao2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14221"}
tags: ['Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have shown tremendous success in following user instructions and generating helpful responses. Nevertheless their robustness is still far from optimal as they may generate significantly inconsistent responses due to minor changes in the verbalized instructions. Recent literature has explored this inconsistency issue highlighting the importance of continued improvement in the robustness of response generation. However systematic analysis and solutions are still lacking. In this paper we quantitatively define the inconsistency problem and propose a two45;stage training framework consisting of instruction45;augmented supervised fine45;tuning and consistency alignment training. The first stage helps a model generalize on following instructions via similar instruction augmentations. In the second stage we improve the diversity and help the model understand which responses are more aligned with human expectations by differentiating subtle differences in similar responses. The training process is accomplished by self45;rewards inferred from the trained model at the first stage without referring to external human preference resources. We conduct extensive experiments on recent publicly available LLMs on instruction45;following tasks and demonstrate the effectiveness of our training framework.
