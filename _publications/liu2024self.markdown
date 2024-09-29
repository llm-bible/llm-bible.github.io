---
layout: publication
title: Self45;reflection Outcome Is Sensitive To Prompt Construction
authors: Liu Fengyuan, Aldahoul Nouar, Eady Gregory, Zaki Yasir, Alshebli Bedoor, Rahwan Talal
conference: "Arxiv"
year: 2024
bibkey: liu2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10400"}
  - {name: "Code", url: "https://github.com/Michael98Liu/mixture&#45;of&#45;prompts"}
tags: ['Ethics And Bias', 'Has Code', 'Prompting']
---
Large language models (LLMs) demonstrate impressive zero45;shot and few45;shot reasoning capabilities. Some propose that such capabilities can be improved through self45;reflection i.e. letting LLMs reflect on their own output to identify and correct mistakes in the initial responses. However despite some evidence showing the benefits of self45;reflection recent studies offer mixed results. Here we aim to reconcile these conflicting findings by first demonstrating that the outcome of self45;reflection is sensitive to prompt wording; e.g. LLMs are more likely to conclude that it has made a mistake when explicitly prompted to find mistakes. Consequently idiosyncrasies in reflection prompts may lead LLMs to change correct responses unnecessarily. We show that most prompts used in the self45;reflection literature are prone to this bias. We then propose different ways of constructing prompts that are conservative in identifying mistakes and show that self45;reflection using such prompts results in higher accuracy. Our findings highlight the importance of prompt engineering in self45;reflection tasks. We release our code at https://github.com/Michael98Liu/mixture&#45;of&#45;prompts.
