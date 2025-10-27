---
layout: page
title: Research
permalink: /research/
---

The **Nordic AI Safety Lab** develops methods to understand and control AI systems. We believe that interpretability—understanding the internal mechanisms of AI—is essential for achieving meaningful control and ensuring safety.

## Research Areas

Our research is organized around five interconnected themes:

### Interpretability & Transparency

Understanding how AI systems work internally is foundational to safety. We develop methods to trace and visualize the mechanisms underlying AI behavior, focusing on:
- Mechanistic interpretability of language models and neural agents
- Causal analysis of internal representations and their effects on behavior
- Methods for making AI decision-making processes transparent and auditable

**Publications:**

{% include publication.html
    title="Learning and communication pressures in neural networks: Lessons from emergent communication"
    authors="Lukas Galke, Limor Raviv"
    venue="Language Development Research 5(1)"
    year="2025"
    paper_url=""
    authorcopy_url=""
%}

{% include publication.html
    title="Deep neural networks and humans both benefit from compositional language structure"
    authors="Lukas Galke, Yoav Ram, Limor Raviv"
    venue="Nature Communications 15:10816"
    year="2024"
    paper_url=""
    code_url=""
    data_url=""
%}

{% include publication.html
    title="Tokenization and Morphology in Multilingual Language Models: A Comparative Analysis of mT5 and ByT5"
    authors="Thao Anh Dang, Limor Raviv, Lukas Galke"
    venue="Proceedings of the 8th International Conference on Natural Language and Speech Processing (ICNLSP-2025)"
    year="2025"
    paper_url="https://aclanthology.org/2025.icnlsp-1.24/"
%}

{% include publication.html
    title="Isolating Culture Neurons in Multilingual Large Language Models"
    authors="Danial Namazifard, Lukas Galke"
    venue="IJCNLP-AACL 2025"
    year="2025"
    authorcopy_url="https://arxiv.org/abs/2508.02241"
%}

### Control & Containment

Interpretability insights enable better control mechanisms. We work on:
- Interpretability-informed intervention techniques for steering AI behavior
- Containment strategies for limiting unintended AI capabilities
- Safe deployment frameworks that leverage mechanistic understanding

**Publications:**

{% include publication.html
    title="Guarded Query Routing for Large Language Models"
    authors="Richard Šléher, William Brach, Tibor Sloboda, Kristián Košťál, and Lukas Galke"
    venue="European Conference on Artificial Intelligence"
    year="2025"
    authorcopy_url=""
%}

### Agentic & Multi-Agent Safety

AI agents introduce unique safety challenges, especially when multiple agents interact. Our research addresses:
- Safety in emergent communication and coordination between AI agents
- Robustness and alignment in agentic systems
- Monitoring and control of goal-directed AI behavior

**Publications:**

{% include publication.html
    title="Super-additive Cooperation in Language Model Agents"
    authors="Filippo Tonini, Lukas Galke"
    venue="3rd International Conference on Frontiers of Artificial Intelligence, Ethics, and Multidisciplinary Applications"
    year="2025"
    authorcopy_url="https://arxiv.org/abs/2508.15510"
    project_url="https://github.com/pippot/Superadditive-cooperation-LLMs"
%}

### Safety Evaluation

Rigorous evaluation is critical for assessing AI safety properties. We develop:

- Benchmarks and metrics for interpretability and control
- Methods for detecting potential safety failures before deployment
- Frameworks for continual safety assessment in evolving systems

**Publications:**

{% include publication.html
    title="Lifelong Learning on Evolving Graphs Under the Constraints of Imbalanced Classes and New Classes"
    authors="Lukas Galke, Iacopo Vagliano, Benedikt Franke, Tobias Zielke, Marcel Hoffmann, and Ansgar Scherp"
    abstract="Lifelong graph learning deals with the problem of continually adapting graph neural network (GNN) models to changes in evolving graphs. We address two critical challenges of lifelong graph learning in this work: dealing with new classes and tackling imbalanced class distributions. The combination of these two challenges is particularly relevant since newly emerging classes typically resemble only a tiny fraction of the data, adding to the already skewed class distribution. We make several contributions: First, we show that the amount of unlabeled data does not influence the results, which is an essential prerequisite for lifelong learning on a sequence of tasks. Second, we experiment with different label rates and show that our methods can perform well with only a tiny fraction of annotated nodes. Third, we propose the gDOC method to detect new classes under the constraint of having an imbalanced class distribution. The critical ingredient is a weighted binary cross-entropy loss function to account for the class imbalance. Moreover, we demonstrate combinations of gDOC with various base GNN models such as GraphSAGE, Simplified Graph Convolution, and Graph Attention Networks. Lastly, our k-neighborhood time difference measure provably normalizes the temporal changes across different graph datasets. With extensive experimentation, we find that the proposed gDOC method is consistently better than a naive adaption of DOC to graphs. Specifically, in experiments using the smallest history size, the out-of-distribution detection score of gDOC is 0.09 compared to 0.01 for DOC. Furthermore, gDOC achieves an Open-F1 score, a combined measure of in-distribution classification and out-of-distribution detection, of 0.33 compared to 0.25 of DOC (32% increase)."
    venue="Neural Networks 164"
    year="2023"
    paper_url="https://doi.org/10.1016/j.neunet.2023.04.022"
    authorcopy_url="https://pure.mpg.de/rest/items/item_3368482_4/component/file_3510107/content"
    data_url="https://doi.org/10.5281/zenodo.3764770"
    code_url="https://github.com/lgalke/lifelong-learning"
%}

{% include publication.html
    title="Bag-of-Words vs. Graph vs. Sequence in Text Classification: Questioning the Necessity of Text-Graphs and the Surprising Strength of a Wide MLP"
    authors="Lukas Galke and Ansgar Scherp"
    abstract="Graph neural networks have triggered a resurgence of graph-based text classification methods, defining today's state of the art. We show that a wide multi-layer perceptron (MLP) using a Bag-of-Words (BoW) outperforms the recent graph-based models TextGCN and HeteGCN in an inductive text classification setting and is comparable with HyperGAT. Moreover, we fine-tune a sequence-based BERT and a lightweight DistilBERT model, which both outperform all state-of-the-art models. These results question the importance of synthetic graphs used in modern text classifiers. In terms of efficiency, DistilBERT is still twice as large as our BoW-based wide MLP, while graph-based models like TextGCN require setting up an 𝒪(N^2) graph, where N is the vocabulary plus corpus size. Finally, since Transformers need to compute 𝒪(L^2) attention weights with sequence length L, the MLP models show higher training and inference speeds on datasets with long sequences."
    venue="Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)"
    year="2022"
    paper_url="https://aclanthology.org/2022.acl-long.279"
    data_url=""
    code_url="https://github.com/lgalke/text-clf-baselines"
%}

### Sustainability & Resource Impact

AI safety extends beyond technical robustness to encompass environmental and societal sustainability. We investigate:

- Measuring and reducing the carbon footprint of AI systems
- Transparency in AI supply chains and resource dependencies
- Frameworks for responsible innovation that balance capabilities with sustainability
- Trade-offs between model performance, safety, and environmental impact

**Publications:**

{% include publication.html
    title="Continual Quantization-Aware Pre-Training: When to transition from 16-bit to 1.58-bit pre-training for BitNet language models?"
    authors="Jacob Nielsen, Peter Schneider-Kamp, and Lukas Galke"
    venue="ACL 2025 Findings"
    year="2025"
    paper_url=""
%}

