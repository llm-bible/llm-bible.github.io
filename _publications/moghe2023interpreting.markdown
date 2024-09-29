---
layout: publication
title: 'Interpreting User Requests In The Context Of Natural Language Standing Instructions'
authors: Moghe Nikita, Xia Patrick, Andreas Jacob, Eisner Jason, Van Durme Benjamin, Jhamtani Harsh
conference: "Arxiv"
year: 2023
bibkey: moghe2023interpreting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09796"}
tags: ['Applications', 'Prompting', 'Tools']
---
Users of natural language interfaces generally powered by Large Language Models (LLMs)often must repeat their preferences each time they make a similar request. We describe an approach to LLM-based dialogue modeling in which persistent user constraints and preferences -- collectively termed standing instructions -- as additional context for such interfaces. For example when a user states Im hungry a previously expressed preference for Persian food can be automatically added to the LLM prompt influencing the search for relevant restaurants. We develop NLSI a language-to-program dataset consisting of over 2.4K dialogues spanning 17 domains where each dialogue is paired with a user profile (a set of users specific standing instructions) and corresponding structured representations (API calls). A key challenge in NLSI is to identify which subset of the standing instructions is applicable to a given dialogue. NLSI contains diverse phenomena from simple preferences to interdependent instructions such as triggering a hotel search whenever the user is booking tickets to an event. We conduct experiments on NLSI using prompting with large language models and various retrieval approaches achieving a maximum of 44.737; exact match on API prediction. Our results demonstrate the challenges in identifying the relevant standing instructions and their interpretation into API calls.
