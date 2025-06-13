---
layout: publication
title: 'Clicksight: Interpreting Student Clickstreams To Reveal Insights On Learning Strategies Via Llms'
authors: Bahar Radmehr, Ekaterina Shved, Fatma Betül Güreş, Adish Singla, Tanja Käser
conference: "Arxiv"
year: 2025
bibkey: radmehr2025interpreting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15410"}
tags: ['Prompting']
---
Clickstream data from digital learning environments offer valuable insights into students' learning behaviors, but are challenging to interpret due to their high dimensionality and granularity. Prior approaches have relied mainly on handcrafted features, expert labeling, clustering, or supervised models, therefore often lacking generalizability and scalability. In this work, we introduce ClickSight, an in-context Large Language Model (LLM)-based pipeline that interprets student clickstreams to reveal their learning strategies. ClickSight takes raw clickstreams and a list of learning strategies as input and generates textual interpretations of students' behaviors during interaction. We evaluate four different prompting strategies and investigate the impact of self-refinement on interpretation quality. Our evaluation spans two open-ended learning environments and uses a rubric-based domain-expert evaluation. Results show that while LLMs can reasonably interpret learning strategies from clickstreams, interpretation quality varies by prompting strategy, and self-refinement offers limited improvement. ClickSight demonstrates the potential of LLMs to generate theory-driven insights from educational interaction data.
