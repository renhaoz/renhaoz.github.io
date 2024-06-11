---
title: "Learning to Edit Visual Programs with Self-Supervision"
collection: publications
permalink: /publication/2024-06-04-Learning-to-Edit-Visual-Programs-with-Self-Supervision
date: 2024-06-04
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2406.02383'
citation: 'Jones, R. K., Zhang, R., Ganeshan, A., & Ritchie, D. (2024). Learning to Edit Visual Programs with Self-Supervision. arXiv preprint arXiv:2406.02383.'
---

<a href='https://arxiv.org/abs/2406.02383'>Download paper here</a>

We design a system that learns how to edit visual programs. Our edit network consumes a complete input program and a visual target. From this input, we task our network with predicting a local edit operation that could be applied to the input program to improve its similarity to the target. In order to apply this scheme for domains that lack program annotations, we develop a self-supervised learning approach that integrates this edit network into a bootstrapped finetuning loop along with a network that predicts entire programs in one-shot. Our joint finetuning scheme, when coupled with an inference procedure that initializes a population from the one-shot model and evolves members of this population with the edit network, helps to infer more accurate visual programs. Over multiple domains, we experimentally compare our method against the alternative of using only the one-shot model, and find that even under equal search-time budgets, our editing-based paradigm provides significant advantages.

Citation: Jones, R. K., Zhang, R., Ganeshan, A., & Ritchie, D. (2024). Learning to Edit Visual Programs with Self-Supervision. arXiv preprint arXiv:2406.02383.