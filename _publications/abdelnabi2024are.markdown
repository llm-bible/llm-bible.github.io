---
layout: publication
title: Are you still on track! Catching LLM Task Drift with Activations
authors: Abdelnabi Sahar, Fay Aideen, Cherubin Giovanni, Salem Ahmed, Fritz Mario, Paverd Andrew
conference: "Arxiv"
year: 2024
bibkey: abdelnabi2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00799"}
tags: ['ARXIV', 'Interpretability', 'LLM']
---
Large Language Models (LLMs) are routinely used in retrieval-augmented applications to orchestrate tasks and process inputs from users and other sources. These inputs even in a single LLM interaction can come from a variety of sources of varying trustworthiness and provenance. This opens the door to prompt injection attacks where the LLM receives and acts upon instructions from supposedly data-only sources thus deviating from the users original instructions. We define this as task drift and we propose to catch it by scanning and analyzing the LLMs activations. We compare the LLMs activations before and after processing the external input in order to detect whether this input caused instruction drift. We develop two probing methods and find that simply using a linear classifier can detect drift with near perfect ROC AUC on an out-of-distribution test set. We show that this approach generalizes surprisingly well to unseen task domains such as prompt injections jailbreaks and malicious instructions without being trained on any of these attacks. Our setup does not require any modification of the LLM (e.g. fine-tuning) or any text generation thus maximizing deployability and cost efficiency and avoiding reliance on unreliable model output. To foster future research on activation-based task inspection decoding and interpretability we will release our large-scale TaskTracker toolkit comprising a dataset of over 500K instances representations from 5 SoTA language models and inspection tools.
