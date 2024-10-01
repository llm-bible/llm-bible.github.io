---
layout: publication
title: 'Decoding At The Speed Of Thought: Harnessing Parallel Decoding Of Lexical Units For Llms'
authors: Sun Chenxi, Zhang Hongzhi, Lin Zijia, Zhang Jingyuan, Zhang Fuzheng, Wang Zhongyuan, Chen Bin, Song Chengru, Zhang Di, Gai Kun, Xiong Deyi
conference: "Arxiv"
year: 2024
bibkey: sun2024decoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15208"}
  - {name: "Code", url: "https://github.com/tjunlp-lab/Lexical-Unit-Decoding-LUD-"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Model Architecture']
---
"Large language models have demonstrated exceptional capability in natural language understanding and generation. However, their generation speed is limited by the inherently sequential nature of their decoding process, posing challenges for real-time applications. This paper introduces Lexical Unit Decoding (LUD), a novel decoding methodology implemented in a data-driven manner, accelerating the decoding process without sacrificing output quality. The core of our approach is the observation that a pre-trained language model can confidently predict multiple contiguous tokens, forming the basis for a \textit\{lexical unit\}, in which these contiguous tokens could be decoded in parallel. Extensive experiments validate that our method substantially reduces decoding time while maintaining generation quality, i.e., 33\&#37; speed up on natural language generation with no quality loss, and 30\&#37; speed up on code generation with a negligible quality loss of 3\&#37;. Distinctively, LUD requires no auxiliary models and does not require changes to existing architectures. It can also be integrated with other decoding acceleration methods, thus achieving an even more pronounced inference efficiency boost. We posit that the foundational principles of LUD could define a new decoding paradigm for future language models, enhancing their applicability for a broader spectrum of applications. All codes are be publicly available at https://github.com/tjunlp-lab/Lexical-Unit-Decoding-LUD-. Keywords: Parallel Decoding, Lexical Unit Decoding, Large Language Model"
