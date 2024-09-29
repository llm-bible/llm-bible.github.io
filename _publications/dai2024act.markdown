---
layout: publication
title: ACT45;MNMT Auto45;constriction Turning For Multilingual Neural Machine Translation
authors: Dai Shaojie, Liu Xin, Luo Ping, Yu Yue
conference: "Arxiv"
year: 2024
bibkey: dai2024act
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.06745"}
tags: ['Applications', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large language model (LLM) has achieved promising performance in multilingual machine translation tasks through zero/few45;shot prompts or prompt45;tuning. However due to the mixture of multilingual data during the pre45;training of LLM the LLM45;based translation models face the off45;target issue in both prompt45;based methods including a series of phenomena namely instruction misunderstanding translation with wrong language and over45;generation. For this issue this paper introduces an textbf123;underline123;A125;125;uto45;textbf123;underline123;C125;125;onstriction textbf123;underline123;T125;125;urning mechanism for textbf123;underline123;M125;125;ultilingual textbf123;underline123;N125;125;eural textbf123;underline123;M125;125;achine textbf123;underline123;T125;125;ranslation (model) which is a novel supervised fine45;tuning mechanism and orthogonal to the traditional prompt45;based methods. In this method model automatically constructs a constrained template in the target side by adding trigger tokens ahead of the ground truth. Furthermore trigger tokens can be arranged and combined freely to represent different task semantics and they can be iteratively updated to maximize the label likelihood. Experiments are performed on WMT test sets with multiple metrics and the experimental results demonstrate that model achieves substantially improved performance across multiple translation directions and reduce the off45;target phenomena in the translation.
