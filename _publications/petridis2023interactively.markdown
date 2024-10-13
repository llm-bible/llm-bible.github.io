---
layout: publication
title: 'Constitutionmaker: Interactively Critiquing Large Language Models By Converting Feedback Into Principles'
authors: Petridis Savvas, Wedin Ben, Wexler James, Donsbach Aaron, Pushkarna Mahima, Goyal Nitesh, Cai Carrie J., Terry Michael
conference: "Arxiv"
year: 2023
bibkey: petridis2023interactively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15428"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language model (LLM) prompting is a promising new approach for users to
create and customize their own chatbots. However, current methods for steering
a chatbot's outputs, such as prompt engineering and fine-tuning, do not support
users in converting their natural feedback on the model's outputs to changes in
the prompt or model. In this work, we explore how to enable users to
interactively refine model outputs through their feedback, by helping them
convert their feedback into a set of principles (i.e. a constitution) that
dictate the model's behavior. From a formative study, we (1) found that users
needed support converting their feedback into principles for the chatbot and
(2) classified the different principle types desired by users. Inspired by
these findings, we developed ConstitutionMaker, an interactive tool for
converting user feedback into principles, to steer LLM-based chatbots. With
ConstitutionMaker, users can provide either positive or negative feedback in
natural language, select auto-generated feedback, or rewrite the chatbot's
response; each mode of feedback automatically generates a principle that is
inserted into the chatbot's prompt. In a user study with 14 participants, we
compare ConstitutionMaker to an ablated version, where users write their own
principles. With ConstitutionMaker, participants felt that their principles
could better guide the chatbot, that they could more easily convert their
feedback into principles, and that they could write principles more
efficiently, with less mental demand. ConstitutionMaker helped users identify
ways to improve the chatbot, formulate their intuitive responses to the model
into feedback, and convert this feedback into specific and clear principles.
Together, these findings inform future tools that support the interactive
critiquing of LLM outputs.
