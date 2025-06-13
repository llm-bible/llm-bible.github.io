---
layout: publication
title: 'BP4ER: Bootstrap Prompting For Explicit Reasoning In Medical Dialogue Generation'
authors: Yuhong He, Yongqi Zhang, Shizhu He, Jun Wan
conference: "Arxiv"
year: 2024
bibkey: he2024bootstrap
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.19414'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Model Architecture', 'Tools', 'Prompting', 'Ethics and Bias', 'Interpretability']
---
Medical dialogue generation (MDG) has gained increasing attention due to its
substantial practical value. Previous works typically employ a
sequence-to-sequence framework to generate medical responses by modeling
dialogue context as sequential text with annotated medical entities. While
these methods have been successful in generating fluent responses, they fail to
provide process explanations of reasoning and require extensive entity
annotation. To address these limitations, we propose the method Bootstrap
Prompting for Explicit Reasoning in MDG (BP4ER), which explicitly model MDG's
multi-step reasoning process and iteratively enhance this reasoning process. We
employ a least-to-most prompting strategy to guide a large language model (LLM)
in explicit reasoning, breaking down MDG into simpler sub-questions. These
sub-questions build on answers from previous ones. Additionally, we also
introduce two distinct bootstrapping techniques for prompting, which
autonomously correct errors and facilitate the LLM's explicit reasoning. This
approach eliminates the need for entity annotation and increases the
transparency of the MDG process by explicitly generating the intermediate
reasoning chain. The experimental findings on the two public datasets indicate
that BP4ER outperforms state-of-the-art methods in terms of both objective and
subjective evaluation metrics.
