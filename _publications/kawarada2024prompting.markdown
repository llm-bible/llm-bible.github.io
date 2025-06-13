---
layout: publication
title: 'Prompting For Numerical Sequences: A Case Study On Market Comment Generation'
authors: Masayuki Kawarada, Tatsuya Ishigaki, Hiroya Takamura
conference: "Arxiv"
year: 2024
bibkey: kawarada2024prompting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.02466'}
tags: ['Prompting', 'Language Modeling', 'Applications']
---
Large language models (LLMs) have been applied to a wide range of
data-to-text generation tasks, including tables, graphs, and time-series
numerical data-to-text settings. While research on generating prompts for
structured data such as tables and graphs is gaining momentum, in-depth
investigations into prompting for time-series numerical data are lacking.
Therefore, this study explores various input representations, including
sequences of tokens and structured formats such as HTML, LaTeX, and
Python-style codes. In our experiments, we focus on the task of Market Comment
Generation, which involves taking a numerical sequence of stock prices as input
and generating a corresponding market comment. Contrary to our expectations,
the results show that prompts resembling programming languages yield better
outcomes, whereas those similar to natural languages and longer formats, such
as HTML and LaTeX, are less effective. Our findings offer insights into
creating effective prompts for tasks that generate text from numerical
sequences.
