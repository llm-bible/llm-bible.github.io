---
layout: publication
title: Conditionally Combining Robot Skills Using Large Language Models
authors: Zentner K. R., Julian Ryan, Ichter Brian, Sukhatme Gaurav S.
conference: "Arxiv"
year: 2023
bibkey: zentner2023conditionally
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17019"}
  - {name: "Code", url: "https://github.com/krzentner/language&#45;world/"}
tags: ['Agentic', 'Has Code', 'Reinforcement Learning']
---
This paper combines two contributions. First we introduce an extension of the Meta45;World benchmark which we call Language45;World which allows a large language model to operate in a simulated robotic environment using semi45;structured natural language queries and scripted skills described using natural language. By using the same set of tasks as Meta45;World Language45;World results can be easily compared to Meta45;World results allowing for a point of comparison between recent methods using Large Language Models (LLMs) and those using Deep Reinforcement Learning. Second we introduce a method we call Plan Conditioned Behavioral Cloning (PCBC) that allows finetuning the behavior of high45;level plans using end45;to45;end demonstrations. Using Language45;World we show that PCBC is able to achieve strong performance in a variety of few45;shot regimes often achieving task generalization with as little as a single demonstration. We have made Language45;World available as open45;source software at https://github.com/krzentner/language&#45;world/.
