---
layout: publication
title: 'How Much Do Llms Hallucinate Across Languages? On Multilingual Estimation Of LLM Hallucination In The Wild'
authors: Saad Obaid Ul Islam, Anne Lauscher, Goran Glavaš
conference: "Arxiv"
year: 2025
bibkey: islam2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12769"}
tags: ['Training Techniques', 'Prompting', 'Applications']
---
In the age of misinformation, hallucination -- the tendency of Large Language
Models (LLMs) to generate non-factual or unfaithful responses -- represents the
main risk for their global utility. Despite LLMs becoming increasingly
multilingual, the vast majority of research on detecting and quantifying LLM
hallucination are (a) English-centric and (b) focus on machine translation (MT)
and summarization, tasks that are less common ``in the wild'' than open
information seeking. In contrast, we aim to quantify the extent of LLM
hallucination across languages in knowledge-intensive long-form question
answering. To this end, we train a multilingual hallucination detection model
and conduct a large-scale study across 30 languages and 6 open-source LLM
families. We start from an English hallucination detection dataset and rely on
MT to generate (noisy) training data in other languages. We also manually
annotate gold data for five high-resource languages; we then demonstrate, for
these languages, that the estimates of hallucination rates are similar between
silver (LLM-generated) and gold test sets, validating the use of silver data
for estimating hallucination rates for other languages. For the final rates
estimation, we build a knowledge-intensive QA dataset for 30 languages with
LLM-generated prompts and Wikipedia articles as references. We find that, while
LLMs generate longer responses with more hallucinated tokens for
higher-resource languages, there is no correlation between length-normalized
hallucination rates of languages and their digital representation. Further, we
find that smaller LLMs exhibit larger hallucination rates than larger models.
