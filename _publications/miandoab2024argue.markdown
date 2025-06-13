---
layout: publication
title: '"let''s Argue Both Sides": Argument Generation Can Force Small Models To Utilize Previously Inaccessible Reasoning Capabilities'
authors: Kaveh Eskandari Miandoab, Vasanth Sarathy
conference: "Arxiv"
year: 2024
bibkey: miandoab2024argue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12997"}
tags: ['Prompting']
---
Large Language Models (LLMs), despite achieving state-of-the-art results in a
number of evaluation tasks, struggle to maintain their performance when logical
reasoning is strictly required to correctly infer a prediction. In this work,
we propose Argument Generation as a method of forcing models to utilize their
reasoning capabilities when other approaches such as chain-of-thought reasoning
prove insufficient. Our method involves the generation of arguments for each
possible inference result, and asking the end model to rank the generated
arguments. We show that Argument Generation can serve as an appropriate
substitute for zero-shot prompting techniques without the requirement to add
layers of complexity. Furthermore, we argue that knowledge-probing techniques
such as chain-of-thought reasoning and Argument Generation are only useful when
further reasoning is required to infer a prediction, making them auxiliary to
more common zero-shot approaches. Finally, we demonstrate that our approach
forces larger gains in smaller language models, showcasing a complex
relationship between model size and prompting methods in foundation models.
