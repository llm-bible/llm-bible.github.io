---
layout: publication
title: Evoke Evoking Critical Thinking Abilities in LLMs via Reviewer-Author Prompt Editing
authors: Hu Xinyu, Tang Pengfei, Zuo Simiao, Wang Zihan, Song Bowen, Lou Qiang, Jiao Jian, Charles Denis
conference: "Arxiv"
year: 2023
bibkey: hu2023evoke
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13855"}
tags: ['Pretraining Methods', 'Prompting', 'Tools']
---
Large language models (LLMs) have made impressive progress in natural language processing. These models rely on proper human instructions (or prompts) to generate suitable responses. However the potential of LLMs are not fully harnessed by commonly-used prompting methods many human-in-the-loop algorithms employ ad-hoc procedures for prompt selection; while auto prompt generation approaches are essentially searching all possible prompts randomly and inefficiently. We propose Evoke an automatic prompt refinement framework. In Evoke there are two instances of a same LLM one as a reviewer (LLM-Reviewer) it scores the current prompt; the other as an author (LLM-Author) it edits the prompt by considering the edit history and the reviewers feedback. Such an author-reviewer feedback loop ensures that the prompt is refined in each iteration. We further aggregate a data selection approach to Evoke where only the hard samples are exposed to the LLM. The hard samples are more important because the LLM can develop deeper understanding of the tasks out of them while the model may already know how to solve the easier cases. Experimental results show that Evoke significantly outperforms existing methods. For instance in the challenging task of logical fallacy detection Evoke scores above 80 while all other baseline methods struggle to reach 20.
