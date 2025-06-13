---
layout: publication
title: 'Llms Lost In Translation: M-ALERT Uncovers Cross-linguistic Safety Gaps'
authors: Felix Friedrich, Simone Tedeschi, Patrick Schramowski, Manuel Brack, Roberto Navigli, Huu Nguyen, Bo Li, Kristian Kersting
conference: "Arxiv"
year: 2024
bibkey: friedrich2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15035"}
tags: ['Responsible AI', 'Prompting']
---
Building safe Large Language Models (LLMs) across multiple languages is
essential in ensuring both safe access and linguistic diversity. To this end,
we introduce M-ALERT, a multilingual benchmark that evaluates the safety of
LLMs in five languages: English, French, German, Italian, and Spanish. M-ALERT
includes 15k high-quality prompts per language, totaling 75k, following the
detailed ALERT taxonomy. Our extensive experiments on 10 state-of-the-art LLMs
highlight the importance of language-specific safety analysis, revealing that
models often exhibit significant inconsistencies in safety across languages and
categories. For instance, Llama3.2 shows high unsafety in the category
crime_tax for Italian but remains safe in other languages. Similar differences
can be observed across all models. In contrast, certain categories, such as
substance_cannabis and crime_propaganda, consistently trigger unsafe responses
across models and languages. These findings underscore the need for robust
multilingual safety practices in LLMs to ensure safe and responsible usage
across diverse user communities.
