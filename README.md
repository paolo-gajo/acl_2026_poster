# LLMs Underperform Graph-Based Parsers on Supervised Relation Extraction for Complex Graphs (ACL 2026 poster repo)

## Abstract
Relation extraction represents a fundamental component in the process of creating knowledge graphs, among other applications. Large language models (LLMs) have been adopted as a promising tool for relation extraction, both in supervised and in-context learning settings.
However, in this work we show that their performance still lags behind much smaller architectures when the linguistic graph underlying a text has great complexity.
To demonstrate this, we evaluate four LLMs against a graph-based parser on six relation extraction datasets with sentence graphs of varying sizes and complexities.
Our results show that the graph-based parser increasingly outperforms the LLMs, as the number of relations in the input documents increases. This makes the much lighter graph-based parser a superior choice in the presence of complex linguistic graphs.

## Code

The code for this work can be found at: [graph_parsers_vs_llms](https://github.com/paolo-gajo/graph_parsers_vs_llms)

## Citation

If you would like to use this work, please use the following citation:

```bibtex
@inproceedings{gajo_2026_graphbasedparsersvsllms,
  title = {{LLMs Underperform Graph-Based Parsers on Supervised Relation Extraction for Complex Graphs}},
  author = {Gajo, Paolo and Rosati, Domenic and Sajjad, Hassan and Barr{\'o}n-Cede{\~n}o, Alberto},
  booktitle = {Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics},
  year = {2026}
}
```

## Poster

![ACL 2026 poster](poster_v2.png)
