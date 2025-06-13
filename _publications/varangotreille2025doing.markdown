---
layout: publication
title: 'Doing More With Less -- Implementing Routing Strategies In Large Language Model-based Systems: An Extended Survey'
authors: Clovis Varangot-reille, Christophe Bouvard, Antoine Gourru, Mathieu Ciancone, Marion Schaeffer, François Jacquenet
conference: "Arxiv"
year: 2025
bibkey: varangotreille2025doing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.00409"}
tags: ['Agentic', 'GPT', 'Efficiency and Optimization', 'Survey Paper', 'Model Architecture']
---
Large Language Models (LLM)-based systems, i.e. interconnected elements that
include an LLM as a central component (e.g., conversational agents), are
typically monolithic static architectures that rely on a single LLM for all
user queries. However, they often require different preprocessing strategies,
levels of reasoning, or knowledge. Generalist LLMs (e.g. GPT-4) trained on very
large multi-topic corpora can perform well in a variety of tasks. They require
significant financial, energy, and hardware resources that may not be justified
for basic tasks. This implies potentially investing in unnecessary costs for a
given query. To overcome this problem, a routing mechanism routes user queries
to the most suitable components, such as smaller LLMs or experts in specific
topics. This approach may improve response quality while minimising costs.
Routing can be expanded to other components of the conversational agent
architecture, such as the selection of optimal embedding strategies. This paper
explores key considerations for integrating routing into LLM-based systems,
focusing on resource management, cost definition, and strategy selection. Our
main contributions include a formalisation of the problem, a novel taxonomy of
existing approaches emphasising relevance and resource efficiency, and a
comparative analysis of these strategies in relation to industry practices.
Finally, we identify critical challenges and directions for future research.
