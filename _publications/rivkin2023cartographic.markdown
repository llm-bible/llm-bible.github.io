---
layout: publication
title: 'CARTIER: Cartographic Language Reasoning Targeted At Instruction Execution For Robots'
authors: Rivkin Dmitriy, Kakodkar Nikhil, Hogan Francois, Baghi Bobak H., Dudek Gregory
conference: "Arxiv"
year: 2023
bibkey: rivkin2023cartographic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.11865"}
tags: ['Pretraining Methods', 'RAG']
---
This work explores the capacity of large language models (LLMs) to address problems at the intersection of spatial planning and natural language interfaces for navigation. We focus on following complex instructions that are more akin to natural conversation than traditional explicit procedural directives typically seen in robotics. Unlike most prior work where navigation directives are provided as simple imperative commands (e.g. go to the fridge) we examine implicit directives obtained through conversational interactions.We leverage the 3D simulator AI2Thor to create household query scenarios at scale and augment it by adding complex language queries for 40 object types. We demonstrate that a robot using our method CARTIER (Cartographic lAnguage Reasoning Targeted at Instruction Execution for Robots) can parse descriptive language queries up to 4237; more reliably than existing LLM-enabled methods by exploiting the ability of LLMs to interpret the user interaction in the context of the objects in the scenario.
