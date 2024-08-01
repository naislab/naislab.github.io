---
layout: page
title: Research
permalink: /research/
---

## The Machine Communication Perspective

We investigate machine communication. We understand communication as the transmission of information which can be found in various areas of **machine learning** and **natural language processing**:

1. Machine-to-human communication: How machines learn to communicate with humans, as in **natural language processing** and **language modeling**.
2. Machine-to-machine communication: How machines learn to communicate with other machines. This includes settings like **emergent communication**, where machine learning agents learn to communicate by themselves, but also **knowledge distillation**, where communication happens between teacher and student model.
3. Message-passing neural networks, where the structure of communication is given by the data and models such as **graph neural networks** learn to effectively transmit information from one data point to the other. 
4. Neural communication: How information flows within a neural network model, akin to **representation learning**.

![Machine Communication Overview](/assets/images/MachComm-overview.png)

By viewing those broad fields (Natural Language Processing, Multi-Agent Systems, Learning from Graphs, Representation Learning) through the lens of machine communication, we can discover valuable new links. Specifically, our (current) focus areas are:

1. The causal effects of internal communication on external communication, similar to the young research field of **mechanistic interpretability**.
2. Continual adaptation in the non-stationary environment of communication, using techniques of **lifelong machine learning**
3. Machine communication for **data science**, applying developed methods to gain insights from data, such as corpora of interlinked scholarly documents or social media postings.


## Selected Publications

- [What makes a language easy to deep-learn?](https://arxiv.org/abs/2302.12239) (preprint)
- [Lifelong Learning on Evolving Graphs Under the Constraints of Imbalanced Classes and New Classes](
https://doi.org/10.1016/j.neunet.2023.04.022). Neural Networks 164 (2023), 156-176. -- [paper](https://pure.mpg.de/rest/items/item_3368482_4/component/file_3510107/content) [code](https://github.com/lgalke/lifelong-learning) [data](https://doi.org/10.5281/zenodo.3764770)
- [Bag-of-Words vs. Graph vs. Sequence in Text Classification: Questioning the Necessity of Text-Graphs and the Surprising Strength of a Wide MLP](https://aclanthology.org/2022.acl-long.279). ACL 2022. -- [paper](https://aclanthology.org/2022.acl-long.279) [code](https://github.com/lgalke/text-clf-baselines)
