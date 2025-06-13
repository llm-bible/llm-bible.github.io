---
layout: publication
title: 'Hallucination-free? Assessing The Reliability Of Leading AI Legal Research Tools'
authors: Varun Magesh, Faiz Surani, Matthew Dahl, Mirac Suzgun, Christopher D. Manning, Daniel E. Ho
conference: "Arxiv"
year: 2024
bibkey: magesh2024hallucination
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20362"}
tags: ['Model Architecture', 'Tools', 'RAG', 'GPT', 'Applications']
---
Legal practice has witnessed a sharp rise in products incorporating
artificial intelligence (AI). Such tools are designed to assist with a wide
range of core legal tasks, from search and summarization of caselaw to document
drafting. But the large language models used in these tools are prone to
"hallucinate," or make up false information, making their use risky in
high-stakes domains. Recently, certain legal research providers have touted
methods such as retrieval-augmented generation (RAG) as "eliminating"
(Casetext, 2023) or "avoid[ing]" hallucinations (Thomson Reuters, 2023), or
guaranteeing "hallucination-free" legal citations (LexisNexis, 2023). Because
of the closed nature of these systems, systematically assessing these claims is
challenging. In this article, we design and report on the first preregistered
empirical evaluation of AI-driven legal research tools. We demonstrate that the
providers' claims are overstated. While hallucinations are reduced relative to
general-purpose chatbots (GPT-4), we find that the AI research tools made by
LexisNexis (Lexis+ AI) and Thomson Reuters (Westlaw AI-Assisted Research and
Ask Practical Law AI) each hallucinate between 17% and 33% of the time. We also
document substantial differences between systems in responsiveness and
accuracy. Our article makes four key contributions. It is the first to assess
and report the performance of RAG-based proprietary legal AI tools. Second, it
introduces a comprehensive, preregistered dataset for identifying and
understanding vulnerabilities in these systems. Third, it proposes a clear
typology for differentiating between hallucinations and accurate legal
responses. Last, it provides evidence to inform the responsibilities of legal
professionals in supervising and verifying AI outputs, which remains a central
open question for the responsible integration of AI into law.
