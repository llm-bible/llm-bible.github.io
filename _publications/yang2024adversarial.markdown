---
layout: publication
title: 'On Adversarial Robustness And Out-of-distribution Robustness Of Large Language Models'
authors: April Yang, Jordan Tab, Parth Shah, Paul Kotchavong
conference: "Arxiv"
year: 2024
bibkey: yang2024adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10535"}
tags: ['Security', 'Tools', 'Applications', 'Model Architecture']
---
The increasing reliance on large language models (LLMs) for diverse
applications necessitates a thorough understanding of their robustness to
adversarial perturbations and out-of-distribution (OOD) inputs. In this study,
we investigate the correlation between adversarial robustness and OOD
robustness in LLMs, addressing a critical gap in robustness evaluation. By
applying methods originally designed to improve one robustness type across both
contexts, we analyze their performance on adversarial and out-of-distribution
benchmark datasets. The input of the model consists of text samples, with the
output prediction evaluated in terms of accuracy, precision, recall, and F1
scores in various natural language inference tasks.
  Our findings highlight nuanced interactions between adversarial robustness
and OOD robustness, with results indicating limited transferability between the
two robustness types. Through targeted ablations, we evaluate how these
correlations evolve with different model sizes and architectures, uncovering
model-specific trends: smaller models like LLaMA2-7b exhibit neutral
correlations, larger models like LLaMA2-13b show negative correlations, and
Mixtral demonstrates positive correlations, potentially due to domain-specific
alignment. These results underscore the importance of hybrid robustness
frameworks that integrate adversarial and OOD strategies tailored to specific
models and domains. Further research is needed to evaluate these interactions
across larger models and varied architectures, offering a pathway to more
reliable and generalizable LLMs.
