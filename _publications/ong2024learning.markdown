---
layout: publication
title: 'Routellm: Learning To Route Llms With Preference Data'
authors: Ong Isaac, Almahairi Amjad, Wu Vincent, Chiang Wei-lin, Wu Tianhao, Gonzalez Joseph E., Kadous M Waleed, Stoica Ion
conference: "Arxiv"
year: 2024
bibkey: ong2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18665"}
tags: ['Fine Tuning', 'RAG', 'Tools', 'Training Techniques']
---
Large language models (LLMs) exhibit impressive capabilities across a wide
range of tasks, yet the choice of which model to use often involves a trade-off
between performance and cost. More powerful models, though effective, come with
higher expenses, while less capable models are more cost-effective. To address
this dilemma, we propose several efficient router models that dynamically
select between a stronger and a weaker LLM during inference, aiming to optimize
the balance between cost and response quality. We develop a training framework
for these routers leveraging human preference data and data augmentation
techniques to enhance performance. Our evaluation on widely-recognized
benchmarks shows that our approach significantly reduces costs-by over 2 times
in certain cases-without compromising the quality of responses. Interestingly,
our router models also demonstrate significant transfer learning capabilities,
maintaining their performance even when the strong and weak models are changed
at test time. This highlights the potential of these routers to provide a
cost-effective yet high-performance solution for deploying LLMs.
