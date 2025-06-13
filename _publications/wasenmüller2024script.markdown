---
layout: publication
title: 'Script-based Dialog Policy Planning For Llm-powered Conversational Agents: A Basic Architecture For An "AI Therapist"'
authors: Robert Wasenmüller, Kevin Hilbert, Christoph Benzmüller
conference: "Arxiv"
year: 2024
bibkey: wasenmüller2024script
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.15242'}
tags: ['Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Large Language Model (LLM)-Powered Conversational Agents have the potential
to provide users with scaled behavioral healthcare support, and potentially
even deliver full-scale "AI therapy'" in the future. While such agents can
already conduct fluent and proactive emotional support conversations, they
inherently lack the ability to (a) consistently and reliably act by predefined
rules to align their conversation with an overarching therapeutic concept and
(b) make their decision paths inspectable for risk management and clinical
evaluation -- both essential requirements for an "AI Therapist".
  In this work, we introduce a novel paradigm for dialog policy planning in
conversational agents enabling them to (a) act according to an expert-written
"script" that outlines the therapeutic approach and (b) explicitly transition
through a finite set of states over the course of the conversation. The script
acts as a deterministic component, constraining the LLM's behavior in desirable
ways and establishing a basic architecture for an AI Therapist.
  We implement two variants of Script-Based Dialog Policy Planning using
different prompting techniques and synthesize a total of 100 conversations with
LLM-simulated patients. The results demonstrate the feasibility of this new
technology and provide insights into the efficiency and effectiveness of
different implementation variants.
