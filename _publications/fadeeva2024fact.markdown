---
layout: publication
title: 'Fact-checking The Output Of Large Language Models Via Token-level Uncertainty Quantification'
authors: Fadeeva Ekaterina, Rubashevskii Aleksandr, Shelmanov Artem, Petrakov Sergey, Li Haonan, Mubarak Hamdy, Tsymbalov Evgenii, Kuzmin Gleb, Panchenko Alexander, Baldwin Timothy, Nakov Preslav, Panov Maxim
conference: "Arxiv"
year: 2024
bibkey: fadeeva2024fact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04696"}
tags: ['Ethics And Bias', 'RAG']
---
Large language models (LLMs) are notorious for hallucinating, i.e., producing erroneous claims in their output. Such hallucinations can be dangerous, as occasional factual inaccuracies in the generated text might be obscured by the rest of the output being generally factually correct, making it extremely hard for the users to spot them. Current services that leverage LLMs usually do not provide any means for detecting unreliable generations. Here, we aim to bridge this gap. In particular, we propose a novel fact-checking and hallucination detection pipeline based on token-level uncertainty quantification. Uncertainty scores leverage information encapsulated in the output of a neural network or its layers to detect unreliable predictions, and we show that they can be used to fact-check the atomic claims in the LLM output. Moreover, we present a novel token-level uncertainty quantification method that removes the impact of uncertainty about what claim to generate on the current step and what surface form to use. Our method Claim Conditioned Probability (CCP) measures only the uncertainty of a particular claim value expressed by the model. Experiments on the task of biography generation demonstrate strong improvements for CCP compared to the baselines for seven LLMs and four languages. Human evaluation reveals that the fact-checking pipeline based on uncertainty quantification is competitive with a fact-checking tool that leverages external knowledge.
