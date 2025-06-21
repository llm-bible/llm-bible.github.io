---
layout: publication
title: 'Iris: A Conversational Agent For Complex Tasks'
authors: Ethan Fast, Binbin Chen, Julia Mendelsohn, Jonathan Bassen, Michael Bernstein
conference: Arxiv
year: 2017
citations: 15
bibkey: fast2017conversational
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.05015'}]
tags: [Reinforcement Learning, Agentic]
---
Today's conversational agents are restricted to simple standalone commands.
In this paper, we present Iris, an agent that draws on human conversational
strategies to combine commands, allowing it to perform more complex tasks that
it has not been explicitly designed to support: for example, composing one
command to "plot a histogram" with another to first "log-transform the data".
To enable this complexity, we introduce a domain specific language that
transforms commands into automata that Iris can compose, sequence, and execute
dynamically by interacting with a user through natural language, as well as a
conversational type system that manages what kinds of commands can be combined.
We have designed Iris to help users with data science tasks, a domain that
requires support for command combination. In evaluation, we find that data
scientists complete a predictive modeling task significantly faster (2.6 times
speedup) with Iris than a modern non-conversational programming environment.
Iris supports the same kinds of commands as today's agents, but empowers users
to weave together these commands to accomplish complex goals.