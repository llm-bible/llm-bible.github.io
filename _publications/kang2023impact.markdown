---
layout: publication
title: Impact Of Co45;occurrence On Factual Knowledge Of Large Language Models
authors: Kang Cheongwoong, Choi Jaesik
conference: "Arxiv"
year: 2023
bibkey: kang2023impact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08256"}
  - {name: "Code", url: "https://github.com/CheongWoong/impact&#95;of&#95;cooccurrence&#125;"}
tags: ['Applications', 'Ethics And Bias', 'Has Code', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) often make factually incorrect responses despite their success in various applications. In this paper we hypothesize that relying heavily on simple co45;occurrence statistics of the pre45;training corpora is one of the main factors that cause factual errors. Our results reveal that LLMs are vulnerable to the co45;occurrence bias defined as preferring frequently co45;occurred words over the correct answer. Consequently LLMs struggle to recall facts whose subject and object rarely co45;occur in the pre45;training dataset although they are seen during finetuning. We show that co45;occurrence bias remains despite scaling up model sizes or finetuning. Therefore we suggest finetuning on a debiased dataset to mitigate the bias by filtering out biased samples whose subject45;object co45;occurrence count is high. Although debiased finetuning allows LLMs to memorize rare facts in the training set it is not effective in recalling rare facts unseen during finetuning. Further research in mitigation will help build reliable language models by preventing potential errors. The code is available at url123;https://github.com/CheongWoong/impact&#95;of&#95;cooccurrence&#125;.
