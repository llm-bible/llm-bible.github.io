---
layout: publication
title: Learning To Refine With Fine45;grained Natural Language Feedback
authors: Wadhwa Manya, Zhao Xinyu, Li Junyi Jessy, Durrett Greg
conference: "Arxiv"
year: 2024
bibkey: wadhwa2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02397"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
Recent work has explored the capability of large language models (LLMs) to identify and correct errors in LLM45;generated responses. These refinement approaches frequently evaluate what sizes of models are able to do refinement for what problems but less attention is paid to what effective feedback for refinement looks like. In this work we propose looking at refinement with feedback as a composition of three distinct LLM competencies (1) identification of bad generations; (2) fine45;grained natural language feedback generation; (3) refining with fine45;grained feedback. The first step can be implemented with a high45;performing discriminative model and steps 2 and 3 can be implemented either via prompted or fine45;tuned LLMs. A key property of this approach is that the step 2 critique model can give fine45;grained feedback about errors made possible by offloading the discrimination to a separate model in step 1. We show that models of different capabilities benefit from refining with this approach on the task of improving factual consistency of document grounded summaries. Overall our proposed method consistently outperforms existing end45;to45;end refinement approaches and current trained models not fine45;tuned for factuality critiquing.
