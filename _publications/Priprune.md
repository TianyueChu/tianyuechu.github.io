---
title: "PriPrune: Quantifying and Preserving Privacy in Pruned Federated Learning"
collection: publications
category: manuscripts
permalink: "/publication/2024-11-02-https://dl.acm.org/doi/abs/10.1145/3702241"
excerpt: 'In this paper, we first characterize the privacy offered by pruning. We establish information-theoretic upper bounds on the information leakage from pruned FL and we experimentally validate them under state-of-the-art privacy attacks across different FL pruning schemes. Second, we introduce PriPruneś a privacy-aware algorithm for pruning in FL. PriPrune uses defense pruning masks, which can be applied locally after any pruning algorithm, and adapts the defense pruning rate to jointly optimize privacy and accuracy. Another key idea in the design of PriPrune is Pseudo-Pruning: it undergoes defense pruning within the local model and only sends the pruned model to the server; while the weights pruned out by defense mask are withheld locally for future local training rather than being removed.'
date: 2024-11-02
venue: 'ACM Transactions on Modeling and Performance Evaluation of Computing Systems'
slidesurl: #'http://tianyuechu.github.io/files/slides1.pdf'
paperurl: #'http://tianyuechu.github.io/files/paper1.pdf'
citation: #'Chu, Tianyue, et al. &quot;PriPrune: Quantifying and Preserving Privacy in Pruned Federated Learning.&quot; <i>ACM Transactions on Modeling and Performance Evaluation of Computing Systems</i>. 2024.'
---
In this paper, we first characterize the privacy offered by pruning. We establish information-theoretic upper bounds on the information leakage from pruned FL and we experimentally validate them under state-of-the-art privacy attacks across different FL pruning schemes. Second, we introduce PriPruneś a privacy-aware algorithm for pruning in FL. PriPrune uses defense pruning masks, which can be applied locally after any pruning algorithm, and adapts the defense pruning rate to jointly optimize privacy and accuracy. Another key idea in the design of PriPrune is Pseudo-Pruning: it undergoes defense pruning within the local model and only sends the pruned model to the server; while the weights pruned out by defense mask are withheld locally for future local training rather than being removed.

