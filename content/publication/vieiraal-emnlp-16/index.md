---
title: "Speed-Accuracy Tradeoffs in Tagging with Variable-Order CRFs and Structured Sparsity"
date: 2016-11-01
publishDate: 2020-03-09T15:29:13.538196Z
authors: ["Tim Vieira$^*$", "Ryan Cotterell$^*$", "Jason Eisner"]
publication_types: ["1"]
abstract: "We propose a method for learning the structure of variable-order CRFs, a more flexible variant of higher-order linear-chain CRFs. Variableorder CRFs achieve faster inference by including features for only some of the tag ngrams. Our learning method discovers the useful higher-order features at the same time as it trains their weights, by maximizing an objective that combines log-likelihood with a structured-sparsity regularizer. An active-set outer loop allows the feature set to grow as far as needed. On part-of-speech tagging in 5 randomly chosen languages from the Universal Dependencies dataset, our method of shrinking the model achieved a 2–6x speedup over a baseline, with no significant drop in accuracy."
featured: false
publication: "*Proceedings of the 2016 Conference on Empirical Methods in Natural Language Processing*"
url_pdf: "https://www.aclweb.org/anthology/D16-1206.pdf"
---

