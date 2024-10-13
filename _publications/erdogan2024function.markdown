---
layout: publication
title: 'Tinyagent: Function Calling At The Edge'
authors: Erdogan Lutfi Eren, Lee Nicholas, Jha Siddharth, Kim Sehoon, Tabrizi Ryan, Moon Suhong, Hooper Coleman, Anumanchipalli Gopala, Keutzer Kurt, Gholami Amir
conference: "Arxiv"
year: 2024
bibkey: erdogan2024function
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00608"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'Quantization', 'Tools', 'Training Techniques']
---
Recent large language models (LLMs) have enabled the development of advanced
agentic systems that can integrate various tools and APIs to fulfill user
queries through function calling. However, the deployment of these LLMs on the
edge has not been explored since they typically require cloud-based
infrastructure due to their substantial model size and computational demands.
To this end, we present TinyAgent, an end-to-end framework for training and
deploying task-specific small language model agents capable of function calling
for driving agentic systems at the edge. We first show how to enable accurate
function calling for open-source models via the LLMCompiler framework. We then
systematically curate a high-quality dataset for function calling, which we use
to fine-tune two small language models, TinyAgent-1.1B and 7B. For efficient
inference, we introduce a novel tool retrieval method to reduce the input
prompt length and utilize quantization to further accelerate the inference
speed. As a driving application, we demonstrate a local Siri-like system for
Apple's MacBook that can execute user commands through text or voice input. Our
results show that our models can achieve, and even surpass, the
function-calling capabilities of larger models like GPT-4-Turbo, while being
fully deployed at the edge. We open-source our dataset, models, and installable
package and provide a demo video for our MacBook assistant agent.
