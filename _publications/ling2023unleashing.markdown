---
layout: publication
title: Unleashing The Creative Mind&#58; Language Model As Hierarchical Policy For Improved Exploration On Challenging Problem Solving
authors: Ling Zhan, Fang Yunhao, Li Xuanlin, Mu Tongzhou, Lee Mingu, Pourreza Reza, Memisevic Roland, Su Hao
conference: "Arxiv"
year: 2023
bibkey: ling2023unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.00694"}
  - {name: "Code", url: "https://github.com/lz1oceani/LLM-As-Hierarchical-Policy"}
tags: ['Fine Tuning', 'Has Code', 'In Context Learning', 'Prompting']
---
Large Language Models (LLMs) have achieved tremendous progress yet they still often struggle with challenging reasoning problems. Current approaches address this challenge by sampling or searching detailed and low-level reasoning chains. However these methods are still limited in their exploration capabilities making it challenging for correct solutions to stand out in the huge solution space. In this work we unleash LLMs creative potential for exploring multiple diverse problem solving strategies by framing an LLM as a hierarchical policy via in-context learning. This policy comprises of a visionary leader that proposes multiple diverse high-level problem-solving tactics as hints accompanied by a follower that executes detailed problem-solving processes following each of the high-level instruction. The follower uses each of the leaders directives as a guide and samples multiple reasoning chains to tackle the problem generating a solution group for each leader proposal. Additionally we propose an effective and efficient tournament-based approach to select among these explored solution groups to reach the final answer. Our approach produces meaningful and inspiring hints enhances problem-solving strategy exploration and improves the final answer accuracy on challenging problems in the MATH dataset. Code will be released at https://github.com/lz1oceani/LLM-As-Hierarchical-Policy."
