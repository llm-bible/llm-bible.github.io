---
layout: publication
title: 'Graph-guided Textual Explanation Generation Framework'
authors: Shuzhou Yuan, Jingyi Sun, Ran Zhang, Michael Färber, Steffen Eger, Pepa Atanasova, Isabelle Augenstein
conference: "Arxiv"
year: 2024
bibkey: yuan2024graph
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12318'}
tags: ['Reinforcement Learning', 'RAG', 'Interpretability and Explainability', 'Tools']
---
Natural language explanations (NLEs) are commonly used to provide plausible
free-text explanations of a model's reasoning about its predictions. However,
recent work has questioned their faithfulness, as they may not accurately
reflect the model's internal reasoning process regarding its predicted answer.
In contrast, highlight explanations--input fragments critical for the model's
predicted answers--exhibit measurable faithfulness. Building on this
foundation, we propose G-Tex, a Graph-Guided Textual Explanation Generation
framework designed to enhance the faithfulness of NLEs. Specifically, highlight
explanations are first extracted as faithful cues reflecting the model's
reasoning logic toward answer prediction. They are subsequently encoded through
a graph neural network layer to guide the NLE generation, which aligns the
generated explanations with the model's underlying reasoning toward the
predicted answer. Experiments on T5 and BART using three reasoning datasets
show that G-Tex improves NLE faithfulness by up to 12.18% compared to baseline
methods. Additionally, G-Tex generates NLEs with greater semantic and lexical
similarity to human-written ones. Human evaluations show that G-Tex can
decrease redundant content and enhance the overall quality of NLEs. Our work
presents a novel method for explicitly guiding NLE generation to enhance
faithfulness, serving as a foundation for addressing broader criteria in NLE
and generated text.
