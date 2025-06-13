---
layout: publication
title: 'Are Chatbots Ready For Privacy-sensitive Applications? An Investigation Into Input Regurgitation And Prompt-induced Sanitization'
authors: Aman Priyanshu, Supriti Vijay, Ayush Kumar, Rakshit Naidu, Fatemehsadat Mireshghallah
conference: "Arxiv"
year: 2023
bibkey: priyanshu2023are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15008"}
tags: ['GPT', 'Applications', 'Model Architecture', 'Prompting', 'In-Context Learning']
---
LLM-powered chatbots are becoming widely adopted in applications such as
healthcare, personal assistants, industry hiring decisions, etc. In many of
these cases, chatbots are fed sensitive, personal information in their prompts,
as samples for in-context learning, retrieved records from a database, or as
part of the conversation. The information provided in the prompt could directly
appear in the output, which might have privacy ramifications if there is
sensitive information there. As such, in this paper, we aim to understand the
input copying and regurgitation capabilities of these models during inference
and how they can be directly instructed to limit this copying by complying with
regulations such as HIPAA and GDPR, based on their internal knowledge of them.
More specifically, we find that when ChatGPT is prompted to summarize cover
letters of a 100 candidates, it would retain personally identifiable
information (PII) verbatim in 57.4% of cases, and we find this retention to be
non-uniform between different subgroups of people, based on attributes such as
gender identity. We then probe ChatGPT's perception of privacy-related policies
and privatization mechanisms by directly instructing it to provide compliant
outputs and observe a significant omission of PII from output.
