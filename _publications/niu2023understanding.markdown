---
layout: publication
title: 'Understanding The Role Of Textual Prompts In LLM For Time Series Forecasting: An Adapter View'
authors: Peisong Niu, Tian Zhou, Xue Wang, Liang Sun, Rong Jin
conference: "Arxiv"
year: 2023
bibkey: niu2023understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.14782'}
tags: ['RAG', 'Prompting']
---
In the burgeoning domain of Large Language Models (LLMs), there is a growing
interest in applying LLM to time series forecasting, with multiple studies
focused on leveraging textual prompts to further enhance the predictive
prowess. This study aims to understand how and why the integration of textual
prompts into LLM can effectively improve the prediction accuracy of time
series, which is not obvious at the glance, given the significant domain gap
between texts and time series. Our extensive examination leads us to believe
that (a) adding text prompts is roughly equivalent to introducing additional
adapters, and (b) It is the introduction of learnable parameters rather than
textual information that aligns the LLM with the time series forecasting task,
ultimately enhancing prediction accuracy. Inspired by this discovery, we
developed four adapters that explicitly address the gap between LLM and time
series, and further improve the prediction accuracy. Overall,our work
highlights how textual prompts enhance LLM accuracy in time series forecasting
and suggests new avenues for continually improving LLM-based time series
analysis.
