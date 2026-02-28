---
author_profile: false
title: "Deep model of protein evolution in time generate realistic evolutionary trajectories and functional proteins"
authors: "**Koehl A**, Prillo S, Liu Matthew, Xiong J, Weng L, Savage DF, Song YS"
pub_date: 2026-02-20
journal: #'Nature'
image: '/images/pubs/2026-koehl.png'
pdf: 'http://antoinekoehl.github.io/files/peint.pdf'
pmid: ##29899455
pmcid: ##PMC6317904
---

## Abstract
Models of protein evolution are foundational to biology, underpinning essential techniques such as phylogenetic tree inference, ancestral sequence reconstruction, multiple sequence alignment, variant effect prediction, and protein design. Historically, for computational tractability, these models have relied on the simplifying – but biologically unrealistic – assumption that sites in a given protein evolve independently of each other. A crucial test of any evolutionary model is its ability to simulate realistic evolutionary trajectories, but the independent-sites assumption leads to simulations that poorly reflect the complexity of natural protein evolution. Here we introduce PEINT (Protein Evolution IN Time), a flexible and generalizable deep learning framework for modeling how the entire protein sequence evolves over time while incorporating complex interactions between sites. This framework enables learning realistic patterns of constrained evolutionary transitions directly from millions of protein sequences spanning diverse fold families. Furthermore, unlike classical models that require pre-aligned sequences, PEINT learns indel dynamics directly from raw, unaligned sequences, thereby eliminating potential biases from alignment errors that can lead to incorrect inference of evolutionary patterns. By capturing higher-order epistatic interactions and modeling insertion-deletion processes that classical models typically ignore, PEINT accurately reproduces key signatures of natural evolution, including conservation patterns and family-specific dynamics. When simulating evolution along phylogenetic trees, PEINT generates highly novel sequences that preserve protein function, which we validate through experimental characterization of simulated carbonic anhydrase variants that retain enzymatic activity. PEINT thus enables realistic simulation of protein evolution that explores new sequence space while respecting structural and functional constraints. This evolution-informed generative modeling framework offers a powerful new tool for advancing both phylogenetic inference and protein engineering.