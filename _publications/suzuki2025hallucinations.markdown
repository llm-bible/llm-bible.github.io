---
layout: publication
title: 'Hallucinations Are Inevitable But Can Be Made Statistically Negligible. The "innate" Inevitability Of Hallucinations Cannot Explain Practical LLM Issues'
authors: Atsushi Suzuki, Yulan He, Feng Tian, Zhongyuan Wang
conference: "Arxiv"
year: 2025
bibkey: suzuki2025hallucinations
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.12187'}
tags: ['Training Techniques', 'Model Architecture']
---
Hallucinations, a phenomenon where a language model (LM) generates nonfactual content, pose a significant challenge to the practical deployment of LMs. While many empirical methods have been proposed to mitigate hallucinations, recent studies established a computability-theoretic result showing that any LM will inevitably generate hallucinations on an infinite set of inputs, regardless of the quality and quantity of training datasets and the choice of the language model architecture and training and inference algorithms. Although the computability-theoretic result may seem pessimistic, its significance in practical viewpoints has remained unclear. This paper claims that those "innate" inevitability results from computability theory and diagonal argument, in principle, cannot explain practical issues of LLMs. We demonstrate this claim by presenting a positive theoretical result from a probabilistic perspective. Specifically, we prove that hallucinations can be made statistically negligible, provided that the quality and quantity of the training data are sufficient. Interestingly, our positive result coexists with the computability-theoretic result, implying that while hallucinations on an infinite set of inputs cannot be entirely eliminated, their probability can always be reduced by improving algorithms and training data. By evaluating the two seemingly contradictory results through the lens of information theory, we argue that our probability-theoretic positive result better reflects practical considerations than the computability-theoretic negative result.
