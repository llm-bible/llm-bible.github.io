---
layout: publication
title: 'Can Large Language Models Explain Themselves? A Study Of Llm-generated Self-explanations'
authors: Shiyuan Huang, Siddarth Mamidanna, Shreedhar Jangam, Yilun Zhou, Leilani H. Gilpin
conference: "Arxiv"
year: 2023
bibkey: huang2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.11207"}
tags: ['GPT', 'Survey Paper', 'Applications', 'Interpretability and Explainability', 'Model Architecture', 'Interpretability', 'Prompting']
---
Large language models (LLMs) such as ChatGPT have demonstrated superior
performance on a variety of natural language processing (NLP) tasks including
sentiment analysis, mathematical reasoning and summarization. Furthermore,
since these models are instruction-tuned on human conversations to produce
"helpful" responses, they can and often will produce explanations along with
the response, which we call self-explanations. For example, when analyzing the
sentiment of a movie review, the model may output not only the positivity of
the sentiment, but also an explanation (e.g., by listing the sentiment-laden
words such as "fantastic" and "memorable" in the review). How good are these
automatically generated self-explanations? In this paper, we investigate this
question on the task of sentiment analysis and for feature attribution
explanation, one of the most commonly studied settings in the interpretability
literature (for pre-ChatGPT models). Specifically, we study different ways to
elicit the self-explanations, evaluate their faithfulness on a set of
evaluation metrics, and compare them to traditional explanation methods such as
occlusion or LIME saliency maps. Through an extensive set of experiments, we
find that ChatGPT's self-explanations perform on par with traditional ones, but
are quite different from them according to various agreement metrics, meanwhile
being much cheaper to produce (as they are generated along with the
prediction). In addition, we identified several interesting characteristics of
them, which prompt us to rethink many current model interpretability practices
in the era of ChatGPT(-like) LLMs.
