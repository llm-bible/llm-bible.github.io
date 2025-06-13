---
layout: publication
title: 'Reboost Large Language Model-based Text-to-sql, Text-to-python, And Text-to-function -- With Real Applications In Traffic Domain'
authors: Guanghu Sui, Zhishuai Li, Ziyue Li, Sun Yang, Jingqing Ruan, Hangyu Mao, Rui Zhao
conference: "Arxiv"
year: 2023
bibkey: sui2023reboost
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.18752'}
tags: ['Prompting', 'Applications']
---
The previous state-of-the-art (SOTA) method achieved a remarkable execution
accuracy on the Spider dataset, which is one of the largest and most diverse
datasets in the Text-to-SQL domain. However, during our reproduction of the
business dataset, we observed a significant drop in performance. We examined
the differences in dataset complexity, as well as the clarity of questions'
intentions, and assessed how those differences could impact the performance of
prompting methods. Subsequently, We develop a more adaptable and more general
prompting method, involving mainly query rewriting and SQL boosting, which
respectively transform vague information into exact and precise information and
enhance the SQL itself by incorporating execution feedback and the query
results from the database content. In order to prevent information gaps, we
include the comments, value types, and value samples for columns as part of the
database description in the prompt. Our experiments with Large Language Models
(LLMs) illustrate the significant performance improvement on the business
dataset and prove the substantial potential of our method. In terms of
execution accuracy on the business dataset, the SOTA method scored 21.05, while
our approach scored 65.79. As a result, our approach achieved a notable
performance improvement even when using a less capable pre-trained language
model. Last but not least, we also explore the Text-to-Python and
Text-to-Function options, and we deeply analyze the pros and cons among them,
offering valuable insights to the community.
