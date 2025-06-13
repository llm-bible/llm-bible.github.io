---
layout: publication
title: 'Towards Generating Functionally Correct Code Edits From Natural Language Issue Descriptions'
authors: Sarah Fakhoury, Saikat Chakraborty, Madan Musuvathi, Shuvendu K. Lahiri
conference: "Arxiv"
year: 2023
bibkey: fakhoury2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.03816"}
tags: ['Uncategorized']
---
Large language models (LLMs), such as OpenAI's Codex, have demonstrated their
potential to generate code from natural language descriptions across a wide
range of programming tasks. Several benchmarks have recently emerged to
evaluate the ability of LLMs to generate functionally correct code from natural
language intent with respect to a set of hidden test cases. This has enabled
the research community to identify significant and reproducible advancements in
LLM capabilities. However, there is currently a lack of benchmark datasets for
assessing the ability of LLMs to generate functionally correct code edits based
on natural language descriptions of intended changes. This paper aims to
address this gap by motivating the problem NL2Fix of translating natural
language descriptions of code changes (namely bug fixes described in Issue
reports in repositories) into correct code fixes. To this end, we introduce
Defects4J-NL2Fix, a dataset of 283 Java programs from the popular Defects4J
dataset augmented with high-level descriptions of bug fixes, and empirically
evaluate the performance of several state-of-the-art LLMs for the this task.
Results show that these LLMS together are capable of generating plausible fixes
for 64.6% of the bugs, and the best LLM-based technique can achieve up to
21.20% top-1 and 35.68% top-5 accuracy on this benchmark.
