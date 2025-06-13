---
layout: publication
title: 'Too Many Frames, Not All Useful: Efficient Strategies For Long-form Video QA'
authors: Jongwoo Park, Kanchana Ranasinghe, Kumara Kahatapitiya, Wonjeong Ryu, Donghyun Kim, Michael S. Ryoo
conference: "Arxiv"
year: 2024
bibkey: park2024too
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.09396'}
  - {name: "Code", url: 'https://github.com/jongwoopark7978/LVNet'}
tags: ['Has Code', 'Tools']
---
Long-form videos that span across wide temporal intervals are highly
information redundant and contain multiple distinct events or entities that are
often loosely related. Therefore, when performing long-form video question
answering (LVQA), all information necessary to generate a correct response can
often be contained within a small subset of frames. Recent literature explore
use of large language models (LLMs) in LVQA benchmarks, achieving exceptional
performance, while relying on vision language models (VLMs) to convert all
visual content within videos into natural language. Such VLMs often
independently caption a large number of frames uniformly sampled from long
videos, which is not efficient and can mostly be redundant. Questioning these
decision choices, we explore optimal strategies for key-frame selection that
can significantly reduce these redundancies, namely Hierarchical Keyframe
Selector. Our proposed framework, LVNet, achieves state-of-the-art performance
at a comparable caption scale across three benchmark LVQA datasets: EgoSchema,
NExT-QA, and IntentQA, while also demonstrating a strong performance on videos
up to an hour long in VideoMME. Our code will be released publicly. The code
can be found at https://github.com/jongwoopark7978/LVNet.
