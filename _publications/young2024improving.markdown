---
layout: publication
title: 'Improving Structural Diversity Of Blackbox Llms Via Chain-of-specification Prompting'
authors: Halley Young, Yimeng Zeng, Jacob Gardner, Osbert Bastani
conference: "Arxiv"
year: 2024
bibkey: young2024improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.06186'}
tags: ['Prompting', 'BERT', 'Model Architecture']
---
The capability to generate diverse text is a key challenge facing large
language models (LLMs). Thus far, diversity has been studied via metrics such
as \\(n\\)-gram diversity or diversity of BERT embeddings. However, for these kinds
of diversity, the user has little control over the dimensions along which
diversity is considered. For example, in the poetry domain, one might desire
diversity in terms of rhyme and meter, whereas in the code domain, one might
desire diversity in terms of the kinds of expressions used to solve a problem.
We propose a diversity metric called structural diversity, where the user
provides a mapping from generated text to features capturing the kinds of
diversity that they care about. In addition, we propose a novel strategy called
chain-of-specification (CoS) prompting for improving diversity by first having
the LLM generate a specification encoding one instance of structural features,
and then prompting the LLM to generate text that satisfies these features;
notably, our strategy works with blackbox LLMs. In our experiments, we show
that for structural diversity in the poetry and code domains, CoS significantly
improves diversity compared to several baselines.
