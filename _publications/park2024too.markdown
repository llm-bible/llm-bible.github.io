---
layout: publication
title: Too Many Frames, Not All Useful\:efficient Strategies For Long-form Video QA
authors: Park Jongwoo, Ranasinghe Kanchana, Kahatapitiya Kumara, Ryoo Wonjeong, Kim Donghyun, Ryoo Michael S.
conference: "Arxiv"
year: 2024
bibkey: park2024too
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09396"}
tags: ['Applications', 'Tools']
---
Long-form videos that span across wide temporal intervals are highly information redundant and contain multiple distinct events or entities that are often loosely-related. Therefore when performing long-form video question answering (LVQA)all information necessary to generate a correct response can often be contained within a small subset of frames. Recent literature explore the use of large language models (LLMs) in LVQA benchmarks achieving exceptional performance while relying on vision language models (VLMs) to convert all visual content within videos into natural language. Such VLMs often independently caption a large number of frames uniformly sampled from long videos which is not efficient and can mostly be redundant. Questioning these decision choices we explore optimal strategies for key-frame selection and sequence-aware captioning that can significantly reduce these redundancies. We propose two novel approaches that improve each of aspects namely Hierarchical Keyframe Selector and Sequential Visual LLM. Our resulting framework termed LVNet achieves state-of-the-art performance across three benchmark LVQA datasets. Our code will be released publicly.
