---
layout: publication
title: 'Multi-line Ai-assisted Code Authoring'
authors: Dunay Omer, Cheng Daniel, Tait Adam, Thakkar Parth, Rigby Peter C, Chiu Andy, Ahmad Imad, Ganesan Arun, Maddila Chandra, Murali Vijayaraghavan, Tayyebi Ali, Nagappan Nachiappan
conference: "Arxiv"
year: 2024
bibkey: dunay2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04141"}
tags: ['Efficiency And Optimization', 'Pretraining Methods']
---
"CodeCompose is an AI-assisted code authoring tool powered by large language models (LLMs) that provides inline suggestions to 10's of thousands of developers at Meta. In this paper, we present how we scaled the product from displaying single-line suggestions to multi-line suggestions. This evolution required us to overcome several unique challenges in improving the usability of these suggestions for developers. First, we discuss how multi-line suggestions can have a 'jarring' effect, as the LLM's suggestions constantly move around the developer's existing code, which would otherwise result in decreased productivity and satisfaction. Second, multi-line suggestions take significantly longer to generate; hence we present several innovative investments we made to reduce the perceived latency for users. These model-hosting optimizations sped up multi-line suggestion latency by 2.5x. Finally, we conduct experiments on 10's of thousands of engineers to understand how multi-line suggestions impact the user experience and contrast this with single-line suggestions. Our experiments reveal that (i) multi-line suggestions account for 42&#37; of total characters accepted (despite only accounting for 16&#37; for displayed suggestions) (ii) multi-line suggestions almost doubled the percentage of keystrokes saved for users from 9&#37; to 17&#37;. Multi-line CodeCompose has been rolled out to all engineers at Meta, and less than 1&#37; of engineers have opted out of multi-line suggestions."
