---
title: "Information-Theoretic Probing for Linguistic Structure"
date: 2020-07-01
publishDate: 2020-05-03T13:16:43.441569Z
authors: ["Tiago Pimentel", "Josef Valvoda", "Rowan Hall Maudslay", "Ran Zmigrod", "Adina Williams", "Ryan Cotterell"]
publication_types: ["1"]
abstract: "The success of neural networks on a diverse set of NLP tasks has led researchers to question how much do these networks actually know about natural language. Probes are a natural way of assessing this. When probing, a researcher chooses a linguistic task and trains a supervised model to predict annotation in that linguistic task from the network’s learned representations. If the probe does well, the researcher may conclude that the representations encode knowledge related to the task. A commonly held belief is that using simpler models as probes is better; the logic is that such models will identify linguistic structure, but not learn the task itself. We propose an information-theoretic formalization of probing as estimating mutual information that contradicts this received wisdom: one should always select the highest performing probe one can, even if it is more complex, since it will result in a tighter estimate. The empirical portion of our paper focuses on obtaining tight estimates for how much information BERT knows about parts of speech in a set of five typologically diverse languages that are often underrepresented in parsing research, plus English, totaling six languages. We find BERT accounts for only at most 5% more information than traditional, type-based word embeddings."
featured: false
publication: "*Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics*"
publication_short: "ACL"
links:
url_pdf: papers/pimentel+al.acl20.pdf
---

