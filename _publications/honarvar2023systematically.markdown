---
layout: publication
title: 'Turbulence: Systematically And Automatically Testing Instruction-tuned Large Language Models For Code'
authors: Honarvar Shahin, Van Der Wilk Mark, Donaldson Alastair
conference: "Arxiv"
year: 2023
bibkey: honarvar2023systematically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.14856"}
tags: ['Applications', 'Security']
---
We present a method for systematically evaluating the correctness and robustness of instruction-tuned large language models (LLMs) for code generation via a new benchmark, Turbulence. Turbulence consists of a large set of natural language \\(\textit{question templates}\\), each of which is a programming problem, parameterised so that it can be asked in many different forms. Each question template has an associated \\(\textit{test oracle}\\) that judges whether a code solution returned by an LLM is correct. Thus, from a single question template, it is possible to ask an LLM a \\(\textit{neighbourhood}\\) of very similar programming questions, and assess the correctness of the result returned for each question. This allows gaps in an LLM's code generation abilities to be identified, including \\(\textit{anomalies}\\) where the LLM correctly solves \\(\textit{almost all}\\) questions in a neighbourhood but fails for particular parameter instantiations. We present experiments against five LLMs from OpenAI, Cohere and Meta, each at two temperature configurations. Our findings show that, across the board, Turbulence is able to reveal gaps in LLM reasoning ability. This goes beyond merely highlighting that LLMs sometimes produce wrong code (which is no surprise): by systematically identifying cases where LLMs are able to solve some problems in a neighbourhood but do not manage to generalise to solve the whole neighbourhood, our method is effective at highlighting \\(\textit{robustness}\\) issues. We present data and examples that shed light on the kinds of mistakes that LLMs make when they return incorrect code results.
