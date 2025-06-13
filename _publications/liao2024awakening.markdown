---
layout: publication
title: 'Awakening Augmented Generation: Learning To Awaken Internal Knowledge Of Large Language Models For Question Answering'
authors: Huanxuan Liao, Shizhu He, Yao Xu, Yuanzhe Zhang, Kang Liu, Shengping Liu, Jun Zhao
conference: "Arxiv"
year: 2024
bibkey: liao2024awakening
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15268"}
  - {name: "Code", url: "https://github.com/Xnhyacinth/IAG"}
tags: ['Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Has Code']
---
Retrieval-Augmented-Generation and Generation-Augmented-Generation have been
proposed to enhance the knowledge required for question answering with Large
Language Models (LLMs) by leveraging richer context. However, the former relies
on external resources, and both require incorporating explicit documents into
the context, which increases execution costs and susceptibility to noise data
during inference. Recent works indicate that LLMs model rich knowledge, but it
is often not effectively activated and awakened. Inspired by this, we propose a
novel knowledge-augmented framework, \\(\textbf\{Awakening-Augmented-Generation\}\\)
(AAG), which mimics the human ability to answer questions using only thinking
and recalling to compensate for knowledge gaps, thereby awaking relevant
knowledge in LLMs without relying on external resources. AAG consists of two
key components for awakening richer context. Explicit awakening fine-tunes a
context generator to create a synthetic, compressed document that functions as
symbolic context. Implicit awakening utilizes a hypernetwork to generate
adapters based on the question and synthetic document, which are inserted into
LLMs to serve as parameter context. Experimental results on three datasets
demonstrate that AAG exhibits significant advantages in both open-domain and
closed-book settings, as well as in out-of-distribution generalization. Our
code will be available at \url\{https://github.com/Xnhyacinth/IAG\}.
