---
layout: publication
title: 'Set-based Prompting: Provably Solving The Language Model Order Dependency Problem'
authors: Mcilroy-young Reid, Brown Katrina, Olson Conlan, Zhang Linjun, Dwork Cynthia
conference: "Arxiv"
year: 2024
bibkey: mcilroyyoung2024set
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06581"}
tags: ['Applications', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
"The development of generative language models that can create long and coherent textual outputs via autoregression has lead to a proliferation of uses and a corresponding sweep of analyses as researches work to determine the limitations of this new paradigm. Unlike humans, these 'Large Language Models' (LLMs) are highly sensitive to small changes in their inputs, leading to unwanted inconsistency in their behavior. One problematic inconsistency when LLMs are used to answer multiple-choice questions or analyze multiple inputs is order dependency: the output of an LLM can (and often does) change significantly when sub-sequences are swapped, despite both orderings being semantically identical. In this paper we present Set-Based Prompting, a technique that guarantees the output of an LLM will not have order dependence on a specified set of sub-sequences. We show that this method provably eliminates order dependency, and that it can be applied to any transformer-based LLM to enable text generation that is unaffected by re-orderings. Delving into the implications of our method, we show that, despite our inputs being out of distribution, the impact on expected accuracy is small, where the expectation is over the order of uniformly chosen shuffling of the candidate responses, and usually significantly less in practice. Thus, Set-Based Prompting can be used as a 'dropped-in' method on fully trained models. Finally, we discuss how our method's success suggests that other strong guarantees can be obtained on LLM performance via modifying the input representations."
