---
layout: publication
title: 'Capabilities Of Gemini Models In Medicine'
authors: Khaled Saab, Tao Tu, Wei-hung Weng, Ryutaro Tanno, David Stutz, Ellery Wulczyn, Fan Zhang, Tim Strother, Chunjong Park, Elahe Vedadi, Juanma Zambrano Chaves, Szu-yeu Hu, Mike Schaekermann, Aishwarya Kamath, Yong Cheng, David G. T. Barrett, Cathy Cheung, Basil Mustafa, Anil Palepu, Daniel Mcduff, Le Hou, Tomer Golany, Luyang Liu, Jean-baptiste Alayrac, Neil Houlsby, Nenad Tomasev, Jan Freyberg, Charles Lau, Jonas Kemp, Jeremy Lai, Shekoofeh Azizi, Kimberly Kanada, Siwai Man, Kavita Kulkarni, Ruoxi Sun, Siamak Shakeri, Luheng He, Ben Caine, Albert Webson, Natasha Latysheva, Melvin Johnson, Philip Mansfield, Jian Lu, Ehud Rivlin, Jesper Anderson, Bradley Green, Renee Wong, Jonathan Krause, Jonathon Shlens, Ewa Dominowska, S. M. Ali Eslami, Katherine Chou, Claire Cui, Oriol Vinyals, Koray Kavukcuoglu, James Manyika, Jeff Dean, Demis Hassabis, Yossi Matias, Dale Webster, Joelle Barral, Greg Corrado, Christopher Semturs, S. Sara Mahdavi, Juraj Gottweis, Alan Karthikesalingam, Vivek Natarajan
conference: "Arxiv"
year: 2024
bibkey: saab2024capabilities
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.18416"}
tags: ['Responsible AI', 'Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting', 'Applications', 'In-Context Learning']
---
Excellence in a wide variety of medical applications poses considerable
challenges for AI, requiring advanced reasoning, access to up-to-date medical
knowledge and understanding of complex multimodal data. Gemini models, with
strong general capabilities in multimodal and long-context reasoning, offer
exciting possibilities in medicine. Building on these core strengths of Gemini,
we introduce Med-Gemini, a family of highly capable multimodal models that are
specialized in medicine with the ability to seamlessly use web search, and that
can be efficiently tailored to novel modalities using custom encoders. We
evaluate Med-Gemini on 14 medical benchmarks, establishing new state-of-the-art
(SoTA) performance on 10 of them, and surpass the GPT-4 model family on every
benchmark where a direct comparison is viable, often by a wide margin. On the
popular MedQA (USMLE) benchmark, our best-performing Med-Gemini model achieves
SoTA performance of 91.1% accuracy, using a novel uncertainty-guided search
strategy. On 7 multimodal benchmarks including NEJM Image Challenges and MMMU
(health & medicine), Med-Gemini improves over GPT-4V by an average relative
margin of 44.5%. We demonstrate the effectiveness of Med-Gemini's long-context
capabilities through SoTA performance on a needle-in-a-haystack retrieval task
from long de-identified health records and medical video question answering,
surpassing prior bespoke methods using only in-context learning. Finally,
Med-Gemini's performance suggests real-world utility by surpassing human
experts on tasks such as medical text summarization, alongside demonstrations
of promising potential for multimodal medical dialogue, medical research and
education. Taken together, our results offer compelling evidence for
Med-Gemini's potential, although further rigorous evaluation will be crucial
before real-world deployment in this safety-critical domain.
