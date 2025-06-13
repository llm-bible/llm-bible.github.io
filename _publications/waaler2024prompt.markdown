---
layout: publication
title: 'Prompt Engineering A Schizophrenia Chatbot: Utilizing A Multi-agent Approach For Enhanced Compliance With Prompt Instructions'
authors: Per Niklas Waaler, Musarrat Hussain, Igor Molchanov, Lars Ailo Bongo, Brita Elvevåg
conference: "Arxiv"
year: 2024
bibkey: waaler2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12848"}
tags: ['Responsible AI', 'Agentic', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Ethics and Bias', 'Prompting', 'Applications']
---
Patients with schizophrenia often present with cognitive impairments that may
hinder their ability to learn about their condition. These individuals could
benefit greatly from education platforms that leverage the adaptability of
Large Language Models (LLMs) such as GPT-4. While LLMs have the potential to
make topical mental health information more accessible and engaging, their
black-box nature raises concerns about ethics and safety. Prompting offers a
way to produce semi-scripted chatbots with responses anchored in instructions
and validated information, but prompt-engineered chatbots may drift from their
intended identity as the conversation progresses. We propose a Critical
Analysis Filter for achieving better control over chatbot behavior. In this
system, a team of prompted LLM agents are prompt-engineered to critically
analyze and refine the chatbot's response and deliver real-time feedback to the
chatbot. To test this approach, we develop an informational schizophrenia
chatbot and converse with it (with the filter deactivated) until it oversteps
its scope. Once drift has been observed, AI-agents are used to automatically
generate sample conversations in which the chatbot is being enticed to talk
about out-of-bounds topics. We manually assign to each response a compliance
score that quantifies the chatbot's compliance to its instructions;
specifically the rules about accurately conveying sources and being transparent
about limitations. Activating the Critical Analysis Filter resulted in an
acceptable compliance score (>=2) in 67.0% of responses, compared to only 8.7%
when the filter was deactivated. These results suggest that a self-reflection
layer could enable LLMs to be used effectively and safely in mental health
platforms, maintaining adaptability while reliably limiting their scope to
appropriate use cases.
