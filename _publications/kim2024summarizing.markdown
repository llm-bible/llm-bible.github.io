---
layout: publication
title: 'Sure: Summarizing Retrievals Using Answer Candidates For Open-domain QA Of Llms'
authors: Jaehyung Kim, Jaehyun Nam, Sangwoo Mo, Jongjin Park, Sang-woo Lee, Minjoon Seo, Jung-woo Ha, Jinwoo Shin
conference: "Arxiv"
year: 2024
bibkey: kim2024summarizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.13081"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) have made significant advancements in various
natural language processing tasks, including question answering (QA) tasks.
While incorporating new information with the retrieval of relevant passages is
a promising way to improve QA with LLMs, the existing methods often require
additional fine-tuning which becomes infeasible with recent LLMs. Augmenting
retrieved passages via prompting has the potential to address this limitation,
but this direction has been limitedly explored. To this end, we design a simple
yet effective framework to enhance open-domain QA (ODQA) with LLMs, based on
the summarized retrieval (SuRe). SuRe helps LLMs predict more accurate answers
for a given question, which are well-supported by the summarized retrieval that
could be viewed as an explicit rationale extracted from the retrieved passages.
Specifically, SuRe first constructs summaries of the retrieved passages for
each of the multiple answer candidates. Then, SuRe confirms the most plausible
answer from the candidate set by evaluating the validity and ranking of the
generated summaries. Experimental results on diverse ODQA benchmarks
demonstrate the superiority of SuRe, with improvements of up to 4.6% in exact
match (EM) and 4.0% in F1 score over standard prompting approaches. SuRe also
can be integrated with a broad range of retrieval methods and LLMs. Finally,
the generated summaries from SuRe show additional advantages to measure the
importance of retrieved passages and serve as more preferred rationales by
models and humans.
