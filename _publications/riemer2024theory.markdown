---
layout: publication
title: 'Position: Theory Of Mind Benchmarks Are Broken For Large Language Models'
authors: Matthew Riemer, Zahra Ashktorab, Djallel Bouneffouf, Payel Das, Miao Liu, Justin D. Weisz, Murray Campbell
conference: "Arxiv"
year: 2024
bibkey: riemer2024theory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.19726"}
tags: ['Prompting', 'Agentic', 'Reinforcement Learning']
---
This position paper argues that the majority of theory of mind benchmarks are
broken because of their inability to directly test how large language models
(LLMs) adapt to new partners. This problem stems from the fact that theory of
mind benchmarks for LLMs are overwhelmingly inspired by the methods used to
test theory of mind in humans and fall victim to a fallacy of attributing
human-like qualities to AI agents. We expect that humans will engage in a
consistent reasoning process across various questions about a situation, but
this is known to not be the case for current LLMs. Most theory of mind
benchmarks only measure what we call literal theory of mind: the ability to
predict the behavior of others. Measuring this kind of reasoning is very
informative in testing the ability of agents with self-consistent reasoning.
However, it is important to note the distinction between this and what we
actually care about when this self-consistency cannot be taken for granted. We
call this functional theory of mind: the ability to adapt to agents in-context
following a rational response to predictions about their behavior. We find that
top performing open source LLMs may display strong capabilities in literal
theory of mind, depending on how they are prompted, but seem to struggle with
functional theory of mind -- even when partner policies are exceedingly simple.
Simply put, strong literal theory of mind performance does not necessarily
imply strong functional theory of mind performance. Achieving functional theory
of mind, particularly over long interaction horizons with a partner, is a
significant challenge deserving a prominent role in any meaningful LLM theory
of mind evaluation.
