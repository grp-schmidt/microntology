# microntology
microntology: a lightweight, data-driven controlled vocabulary to describe Earth's microbial habitats.

---

This repository contains reference files for the `microntology`, a controlled vocabulary to describe microbial samples and habitats. A description of `microntology`'s rationale, design and implementation are provided in a preprint:

Fullam A, V Prasoodanan PK, M Kuhn, P Bork, TSB Schmidt. microntology: a lightweight, data-driven controlled vocabulary to describe Earth's microbial habitats. bioRxiv 2026.01.12.698811; doi: https://doi.org/10.64898/2026.01.12.698811

Briefly, `microntology` follows five core design principles: it is
* data-driven, encompassing terms to describe frequent sample types in existing data
* pragmatic and query-oriented, defining terms at intermediate resolutions to facilitate user access and browsing
* shallow, with only few hierarchical levels of classes
* cross-linked between related terms from different hierarchical paths
* designed for parsimonious multi-tagging where individual samples are described by multiple independent terms, rather than a ‘best match’ highly detailed single term

This repository contains the main files required to browse and use `microntology` in practice:

* `micront.owl`. A *Web Ontology Language* format file describing and linking all terms and categories.
* `microntology.terms.tsv`. An equivalent, human-readable `tsv` file reflecting `microntology` terms, categories, hierarchies and crosslinks.

The  `micron.owl` and terms tables are also available as stable release via Zenodo:

Fullam, A., Prasoodanan P K, V., & Schmidt, T. S. B. (2026). microntology: a controlled vocabulary to describe Earth's microbial habitats. (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.18162129

`microntology` annotations of publicly available metagenomic samples are likewise available as stable via Zenodo:

Fullam, A., Prasoodanan P K, V., & Schmidt, T. S. B. (2026). microntology annotations of publicly available metagenomes in the European Nucleotide Archive (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.18164252

