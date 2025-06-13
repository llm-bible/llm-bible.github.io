---
layout: publication
title: 'Wildframe: Comparing Framing In Humans And Llms On Naturally Occurring Texts'
authors: Gili Lior, Liron Nacchace, Gabriel Stanovsky
conference: "Arxiv"
year: 2025
bibkey: lior2025comparing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17091"}
tags: ['Reinforcement Learning']
---
Humans are influenced by how information is presented, a phenomenon known as
the framing effect. Previous work has shown that LLMs may also be susceptible
to framing but has done so on synthetic data and did not compare to human
behavior. We introduce WildFrame, a dataset for evaluating LLM responses to
positive and negative framing, in naturally-occurring sentences, and compare
humans on the same data. WildFrame consists of 1,000 texts, first selecting
real-world statements with clear sentiment, then reframing them in either
positive or negative light, and lastly, collecting human sentiment annotations.
By evaluating eight state-of-the-art LLMs on WildFrame, we find that all models
exhibit framing effects similar to humans (\\(r\geq0.57\\)), with both humans and
models being more influenced by positive rather than negative reframing. Our
findings benefit model developers, who can either harness framing or mitigate
its effects, depending on the downstream application.
