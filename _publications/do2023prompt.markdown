---
layout: publication
title: Prompt Optimization Via Adversarial In45;context Learning
authors: Do Xuan Long, Zhao Yiran, Brown Hannah, Xie Yuxi, Zhao James Xu, Chen Nancy F., Kawaguchi Kenji, Shieh Michael, He Junxian
conference: "Arxiv"
year: 2023
bibkey: do2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02614"}
tags: ['Applications', 'Efficiency And Optimization', 'Language Modeling', 'Prompting', 'Security']
---
We propose a new method Adversarial In45;Context Learning (adv45;ICL) to optimize prompt for in45;context learning (ICL) by employing one LLM as a generator another as a discriminator and a third as a prompt modifier. As in traditional adversarial learning adv45;ICL is implemented as a two45;player game between the generator and discriminator where the generator tries to generate realistic enough output to fool the discriminator. In each round given an input prefixed by task instructions and several exemplars the generator produces an output. The discriminator is then tasked with classifying the generator input45;output pair as model45;generated or real data. Based on the discriminator loss the prompt modifier proposes possible edits to the generator and discriminator prompts and the edits that most improve the adversarial loss are selected. We show that adv45;ICL results in significant improvements over state45;of45;the45;art prompt optimization techniques for both open and closed45;source models on 11 generation and classification tasks including summarization arithmetic reasoning machine translation data45;to45;text generation and the MMLU and big45;bench hard benchmarks. In addition because our method uses pre45;trained models and updates only prompts rather than model parameters it is computationally efficient easy to extend to any LLM and task and effective in low45;resource settings.
