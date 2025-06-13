---
layout: publication
title: 'Diagrammergpt: Generating Open-domain, Open-platform Diagrams Via LLM Planning'
authors: Abhay Zala, Han Lin, Jaemin Cho, Mohit Bansal
conference: "Arxiv"
year: 2023
bibkey: zala2023generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.12128"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'RAG', 'GPT']
---
Text-to-image (T2I) generation has seen significant growth over the past few
years. Despite this, there has been little work on generating diagrams with T2I
models. A diagram is a symbolic/schematic representation that explains
information using structurally rich and spatially complex visualizations (e.g.,
a dense combination of related objects, text labels, directional arrows/lines,
etc.). Existing state-of-the-art T2I models often fail at diagram generation
because they lack fine-grained object layout control when many objects are
densely connected via complex relations such as arrows/lines, and also often
fail to render comprehensible text labels. To address this gap, we present
DiagrammerGPT, a novel two-stage text-to-diagram generation framework
leveraging the layout guidance capabilities of LLMs to generate more accurate
diagrams. In the first stage, we use LLMs to generate and iteratively refine
'diagram plans' (in a planner-auditor feedback loop). In the second stage, we
use a diagram generator, DiagramGLIGEN, and a text label rendering module to
generate diagrams (with clear text labels) following the diagram plans. To
benchmark the text-to-diagram generation task, we introduce AI2D-Caption, a
densely annotated diagram dataset built on top of the AI2D dataset. We show
that our DiagrammerGPT framework produces more accurate diagrams, outperforming
existing T2I models. We also provide comprehensive analysis, including
open-domain diagram generation, multi-platform vector graphic diagram
generation, human-in-the-loop editing, and multimodal planner/auditor LLMs.
