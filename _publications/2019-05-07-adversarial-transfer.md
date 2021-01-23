---
title: "An Empirical Evaluation of Adversarial Robustness under Transfer Learning."
collection: publications
permalink: /publication/2019-05-07-adversarial-transfer
excerpt: 'In this work, we evaluate adversarial robustness in the context of transfer learning from a source trained on CIFAR 100 to a target network trained on CIFAR 10. Specifically, we study the effects of using robust optimisation in the source and target networks. This allows us to identify transfer learning strategies under which adversarial defences are successfully retained, in addition to revealing potential vulnerabilities. We study the extent to which features learnt by a fast gradient sign method (FGSM) and its iterative alternative (PGD) can preserve their defence properties against black and white-box attacks under three different transfer learning strategies. We find that using PGD examples during training on the source task leads to more general robust features that are easier to transfer. Furthermore, under successful transfer, it achieves 5.2% more accuracy against white-box PGD attacks than suitable baselines. Overall, our empirical evaluations give insights on how well adversarial robustness under transfer learning can generalise.'
date: 2019-05-07
venue: 'International Conference on Machine Learning (ICML) 2019, Understanding and Improving Generalisation Workshop'
paperurl: 'https://arxiv.org/pdf/1905.02675.pdf'
citation: 'Davchev, T., Korres, T., Fotiadis, S., Antonopoulos, N. and Ramamoorthy, S., 2019. An empirical evaluation of adversarial robustness under transfer learning. <i>Arxiv preprint</i>. arXiv:1905.02675.'
---

<a href='https://arxiv.org/pdf/1905.02675.pdf'>Download paper here</a>

This paper studies the effects of using robust optimisation in the context of adversarial attacks. This allows us to identify transfer learning strategies under which adversarial defences are successfully retained, in addition to revealing potential vulnerabilities.
