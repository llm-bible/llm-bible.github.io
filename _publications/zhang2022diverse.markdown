---
layout: publication
title: 'Diverse Title Generation For Stack Overflow Posts With Multiple Sampling Enhanced Transformer'
authors: Fengji Zhang, Jin Liu, Yao Wan, Xiao Yu, Xiao Liu, Jacky Keung
conference: "Arxiv"
year: 2022
bibkey: zhang2022diverse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.11523"}
tags: ['Transformer', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods']
---
Stack Overflow is one of the most popular programming communities where
developers can seek help for their encountered problems. Nevertheless, if
inexperienced developers fail to describe their problems clearly, it is hard
for them to attract sufficient attention and get the anticipated answers. We
propose M\\(_3\\)NSCT5, a novel approach to automatically generate multiple post
titles from the given code snippets. Developers may use the generated titles to
find closely related posts and complete their problem descriptions. M\\(_3\\)NSCT5
employs the CodeT5 backbone, which is a pre-trained Transformer model having an
excellent language understanding and generation ability. To alleviate the
ambiguity issue that the same code snippets could be aligned with different
titles under varying contexts, we propose the maximal marginal multiple nucleus
sampling strategy to generate multiple high-quality and diverse title
candidates at a time for the developers to choose from. We build a large-scale
dataset with 890,000 question posts covering eight programming languages to
validate the effectiveness of M\\(_3\\)NSCT5. The automatic evaluation results on
the BLEU and ROUGE metrics demonstrate the superiority of M\\(_3\\)NSCT5 over six
state-of-the-art baseline models. Moreover, a human evaluation with trustworthy
results also demonstrates the great potential of our approach for real-world
application.
