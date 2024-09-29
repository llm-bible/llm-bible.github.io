---
layout: publication
title: Better Zero45;shot Reasoning With Self45;adaptive Prompting
authors: Wan Xingchen, Sun Ruoxi, Dai Hanjun, Arik Sercan O., Pfister Tomas
conference: "Arxiv"
year: 2023
bibkey: wan2023better
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14106"}
tags: ['Prompting']
---
Modern large language models (LLMs) have demonstrated impressive capabilities at sophisticated tasks often through step45;by45;step reasoning similar to humans. This is made possible by their strong few and zero45;shot abilities 45;45; they can effectively learn from a handful of handcrafted completed responses (in45;context examples) or are prompted to reason spontaneously through specially designed triggers. Nonetheless some limitations have been observed. First performance in the few45;shot setting is sensitive to the choice of examples whose design requires significant human effort. Moreover given the diverse downstream tasks of LLMs it may be difficult or laborious to handcraft per45;task labels. Second while the zero45;shot setting does not require handcrafting its performance is limited due to the lack of guidance to the LLMs. To address these limitations we propose Consistency45;based Self45;adaptive Prompting (COSP) a novel prompt design method for LLMs. Requiring neither handcrafted responses nor ground45;truth labels COSP selects and builds the set of examples from the LLM zero45;shot outputs via carefully designed criteria that combine consistency diversity and repetition. In the zero45;shot setting for three different LLMs we show that using only LLM predictions COSP improves performance up to 1537; compared to zero45;shot baselines and matches or exceeds few45;shot baselines for a range of reasoning tasks.
