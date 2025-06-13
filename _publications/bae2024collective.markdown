---
layout: publication
title: 'Collective Critics For Creative Story Generation'
authors: Minwook Bae, Hyounghun Kim
conference: "Arxiv"
year: 2024
bibkey: bae2024collective
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02428'}
tags: ['Reinforcement Learning', 'Tools']
---
Generating a long story of several thousand words with narrative coherence
using Large Language Models (LLMs) has been a challenging task. Previous
research has addressed this challenge by proposing different frameworks that
create a story plan and generate a long story based on that plan. However,
these frameworks have been mainly focusing on maintaining narrative coherence
in stories, often overlooking creativity in story planning and the
expressiveness of the stories generated from those plans, which are desirable
properties to captivate readers' interest. In this paper, we propose Collective
Critics for Creative Story Generation framework (CritiCS), which is composed of
plan refining stage (CrPlan) and story generation stage (CrText), to integrate
a collective revision mechanism that promotes those properties into long-form
story generation process. Specifically, in each stage, a group of LLM critics
and one leader collaborate to incrementally refine drafts of plan and story
throughout multiple rounds. Extensive human evaluation shows that the CritiCS
can significantly enhance story creativity and reader engagement, while also
maintaining narrative coherence. Furthermore, the design of the framework
allows active participation from human writers in any role within the critique
process, enabling interactive human-machine collaboration in story writing.
