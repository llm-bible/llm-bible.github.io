---
layout: publication
title: 'Sleep-time Compute: Beyond Inference Scaling At Test-time'
authors: Kevin Lin, Charlie Snell, Yu Wang, Charles Packer, Sarah Wooders, Ion Stoica, Joseph E. Gonzalez
conference: "Arxiv"
year: 2025
bibkey: lin2025sleep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.13171"}
tags: ['Agentic', 'RAG']
---
Scaling test-time compute has emerged as a key ingredient for enabling large
language models (LLMs) to solve difficult problems, but comes with high latency
and inference cost. We introduce sleep-time compute, which allows models to
"think" offline about contexts before queries are presented: by anticipating
what queries users might ask and pre-computing useful quantities, we can
significantly reduce the compute requirements at test-time. To demonstrate the
efficacy of our method, we create modified versions of two reasoning tasks -
Stateful GSM-Symbolic and Stateful AIME. We find that sleep-time compute can
reduce the amount of test-time compute needed to achieve the same accuracy by ~
5x on Stateful GSM-Symbolic and Stateful AIME and that by scaling sleep-time
compute we can further increase accuracy by up to 13% on Stateful GSM-Symbolic
and 18% on Stateful AIME. Furthermore, we introduce Multi-Query GSM-Symbolic,
which extends GSM-Symbolic by including multiple related queries per context.
By amortizing sleep-time compute across related queries about the same context
using Multi-Query GSM-Symbolic, we can decrease the average cost per query by
2.5x. We then conduct additional analysis to understand when sleep-time compute
is most effective, finding the predictability of the user query to be well
correlated with the efficacy of sleep-time compute. Finally, we conduct a
case-study of applying sleep-time compute to a realistic agentic SWE task.
