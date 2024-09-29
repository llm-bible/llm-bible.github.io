---
layout: publication
title: Can We Rely On LLM Agents To Draft Long45;horizon Plans Lets Take Travelplanner As An Example
authors: Chen Yanan, Pesaranghader Ali, Sadhu Tanmana, Yi Dong Hoon
conference: "Arxiv"
year: 2024
bibkey: chen2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06318"}
tags: ['Agent', 'Agentic', 'Applications', 'Fine Tuning', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) have brought autonomous agents closer to artificial general intelligence (AGI) due to their promising generalization and emergent capabilities. There is however a lack of studies on how LLM45;based agents behave why they could potentially fail and how to improve them particularly in demanding real45;world planning tasks. In this paper as an effort to fill the gap we present our study using a realistic benchmark TravelPlanner where an agent must meet multiple constraints to generate accurate plans. We leverage this benchmark to address four key research questions (1) are LLM agents robust enough to lengthy and noisy contexts when it comes to reasoning and planning (2) can few45;shot prompting adversely impact the performance of LLM agents in scenarios with long context (3) can we rely on refinement to improve plans and (4) can fine45;tuning LLMs with both positive and negative feedback lead to further improvement Our comprehensive experiments indicate that firstly LLMs often fail to attend to crucial parts of a long context despite their ability to handle extensive reference information and few45;shot examples; secondly they still struggle with analyzing the long plans and cannot provide accurate feedback for refinement; thirdly we propose Feedback45;Aware Fine45;Tuning (FAFT) which leverages both positive and negative feedback resulting in substantial gains over Supervised Fine45;Tuning (SFT). Our findings offer in45;depth insights to the community on various aspects related to real45;world planning applications.
