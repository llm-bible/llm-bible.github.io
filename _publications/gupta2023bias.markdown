---
layout: publication
title: Bias Runs Deep Implicit Reasoning Biases In Persona45;assigned Llms
authors: Gupta Shashank, Shrivastava Vaishnavi, Deshpande Ameet, Kalyan Ashwin, Clark Peter, Sabharwal Ashish, Khot Tushar
conference: "Arxiv"
year: 2023
bibkey: gupta2023bias
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.04892"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Fairness', 'GPT', 'Model Architecture', 'Prompting']
---
Recent works have showcased the ability of LLMs to embody diverse personas in their responses exemplified by prompts like You are Yoda. Explain the Theory of Relativity. While this ability allows personalization of LLMs and enables human behavior simulation its effect on LLMs capabilities remains unclear. To fill this gap we present the first extensive study of the unintended side45;effects of persona assignment on the ability of LLMs to perform basic reasoning tasks. Our study covers 24 reasoning datasets 4 LLMs and 19 diverse personas (e.g. an Asian person) spanning 5 socio45;demographic groups. Our experiments unveil that LLMs harbor deep rooted bias against various socio45;demographics underneath a veneer of fairness. While they overtly reject stereotypes when explicitly asked (Are Black people less skilled at mathematics) they manifest stereotypical and erroneous presumptions when asked to answer questions while adopting a persona. These can be observed as abstentions in responses e.g. As a Black person I cant answer this question as it requires math knowledge and generally result in a substantial performance drop. Our experiments with ChatGPT45;3.5 show that this bias is ubiquitous 45; 8037; of our personas demonstrate bias; it is significant 45; some datasets show performance drops of 7037;+; and can be especially harmful for certain groups 45; some personas suffer statistically significant drops on 8037;+ of the datasets. Overall all 4 LLMs exhibit this bias to varying extents with GPT45;445;Turbo showing the least but still a problematic amount of bias (evident in 4237; of the personas). Further analysis shows that these persona45;induced errors can be hard45;to45;discern and hard45;to45;avoid. Our findings serve as a cautionary tale that the practice of assigning personas to LLMs 45; a trend on the rise 45; can surface their deep45;rooted biases and have unforeseeable and detrimental side45;effects.
