---
layout: publication
title: 'Whose Boat Does It Float? Improving Personalization In Preference Tuning Via Inferred User Personas'
authors: Nishant Balepur, Vishakh Padmakumar, Fumeng Yang, Shi Feng, Rachel Rudinger, Jordan Lee Boyd-graber
conference: "Arxiv"
year: 2025
bibkey: balepur2025whose
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.11549"}
tags: ['Training Techniques', 'Prompting', 'Reinforcement Learning']
---
LLMs are aligned to follow input instructions by learning which of two responses users prefer for a prompt. However, such preference data do not convey why users prefer responses that are chosen or rejected, so LLMs trained on these datasets cannot tailor responses to varied user needs. To surface these parameters of personalization, we apply abductive reasoning to preference data, inferring needs and interests of users, i.e., personas, that may prefer either response. We test this idea in two steps: Persona Inference (PI), abductively inferring personas of users who prefer chosen or rejected outputs, and Persona Tailoring (PT), training models to tailor outputs to personas from PI. We show: 1) LLMs infer personas accurately explaining why different users may prefer both chosen or rejected outputs; 2) Training on preference data augmented with PI personas via PT boosts personalization and generalizes to supporting user-written personas; and 3) Rejected response personas form harder personalization evaluations, showing PT better aids users with uncommon preferences versus typical alignment methods. We argue for an abductive view of preferences for personalization, asking not only which response is better but when, why, and for whom.
