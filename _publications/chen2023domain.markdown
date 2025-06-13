---
layout: publication
title: 'SEED: Domain-specific Data Curation With Large Language Models'
authors: Zui Chen, Lei Cao, Sam Madden, Tim Kraska, Zeyuan Shang, Ju Fan, Nan Tang, Zihui Gu, Chunwei Liu, Michael Cafarella
conference: "Arxiv"
year: 2023
bibkey: chen2023domain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00749"}
tags: ['Training Techniques', 'Applications', 'Few-Shot', 'Tools']
---
Data curation tasks that prepare data for analytics are critical for turning
data into actionable insights. However, due to the diverse requirements of
applications in different domains, generic off-the-shelf tools are typically
insufficient. As a result, data scientists often have to develop
domain-specific solutions tailored to both the dataset and the task, e.g.
writing domain-specific code or training machine learning models on a
sufficient number of annotated examples. This process is notoriously difficult
and time-consuming. We present SEED, an LLM-as-compiler approach that
automatically generates domain-specific data curation solutions via Large
Language Models (LLMs). Once the user describes a task, input data, and
expected output, the SEED compiler produces a hybrid pipeline that combines LLM
querying with more cost-effective alternatives, such as vector-based caching,
LLM-generated code, and small models trained on LLM-annotated data. SEED
features an optimizer that automatically selects from the four LLM-assisted
modules and forms a hybrid execution pipeline that best fits the task at hand.
To validate this new, revolutionary approach, we conducted experiments on \\(9\\)
datasets spanning over \\(5\\) data curation tasks. In comparison to solutions that
use the LLM on every data record, SEED achieves state-of-the-art or comparable
few-shot performance, while significantly reducing the number of LLM calls.
