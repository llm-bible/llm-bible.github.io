---
layout: publication
title: When Do Prompting And Prefix45;tuning Work A Theory Of Capabilities And Limitations
authors: Petrov Aleksandar, Torr Philip H. S., Bibi Adel
conference: "Arxiv"
year: 2023
bibkey: petrov2023when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.19698"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Prompting']
---
Context45;based fine45;tuning methods including prompting in45;context learning soft prompting (also known as prompt tuning) and prefix45;tuning have gained popularity due to their ability to often match the performance of full fine45;tuning with a fraction of the parameters. Despite their empirical successes there is little theoretical understanding of how these techniques influence the internal computation of the model and their expressiveness limitations. We show that despite the continuous embedding space being more expressive than the discrete token space soft45;prompting and prefix45;tuning are potentially less expressive than full fine45;tuning even with the same number of learnable parameters. Concretely context45;based fine45;tuning cannot change the relative attention pattern over the content and can only bias the outputs of an attention layer in a fixed direction. This suggests that while techniques like prompting in45;context learning soft prompting and prefix45;tuning can effectively elicit skills present in the pretrained model they may not be able to learn novel tasks that require new attention patterns.
