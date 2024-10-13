---
layout: publication
title: 'LPML: Llm-prompting Markup Language For Mathematical Reasoning'
authors: Yamauchi Ryutaro, Sonoda Sho, Sannai Akiyoshi, Kumagai Wataru
conference: "Arxiv"
year: 2023
bibkey: yamauchi2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.13078"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Tools']
---
In utilizing large language models (LLMs) for mathematical reasoning,
addressing the errors in the reasoning and calculation present in the generated
text by LLMs is a crucial challenge. In this paper, we propose a novel
framework that integrates the Chain-of-Thought (CoT) method with an external
tool (Python REPL). We discovered that by prompting LLMs to generate structured
text in XML-like markup language, we could seamlessly integrate CoT and the
external tool and control the undesired behaviors of LLMs. With our approach,
LLMs can utilize Python computation to rectify errors within CoT. We applied
our method to ChatGPT (GPT-3.5) to solve challenging mathematical problems and
demonstrated that combining CoT and Python REPL through the markup language
enhances the reasoning capability of LLMs. Our approach enables LLMs to write
the markup language and perform advanced mathematical reasoning using only
zero-shot prompting.
