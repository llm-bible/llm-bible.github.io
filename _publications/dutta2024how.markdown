---
layout: publication
title: How to think step-by-step A mechanistic understanding of chain-of-thought reasoning
authors: Dutta Subhabrata, Singh Joykirat, Chakrabarti Soumen, Chakraborty Tanmoy
conference: "Arxiv"
year: 2024
bibkey: dutta2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18312"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Despite superior reasoning prowess demonstrated by Large Language Models (LLMs) with Chain-of-Thought (CoT) prompting a lack of understanding prevails around the internal mechanisms of the models that facilitate CoT generation. This work investigates the neural sub-structures within LLMs that manifest CoT reasoning from a mechanistic point of view. From an analysis of Llama-2 7B applied to multistep reasoning over fictional ontologies we demonstrate that LLMs deploy multiple parallel pathways of answer generation for step-by-step reasoning. These parallel pathways provide sequential answers from the input question context as well as the generated CoT. We observe a functional rift in the middle layers of the LLM. Token representations in the initial half remain strongly biased towards the pretraining prior with the in-context prior taking over in the later half. This internal phase shift manifests in different functional components attention heads that write the answer token appear in the later half attention heads that move information along ontological relationships appear in the initial half and so on. To the best of our knowledge this is the first attempt towards mechanistic investigation of CoT reasoning in LLMs.
