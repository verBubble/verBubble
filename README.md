### Hi, I'm Xinyue Zhang 👋

DPhil in Computer Science at the University of Oxford.
I design algorithms for complex reasoning systems, prove them correct, and build and evaluate them at scale.
[Google Scholar](https://scholar.google.com/citations?user=HrDe_SkAAAAJ&hl=en)

### Selected Research

**Efficient reasoning in rule-based systems**: PhD research, University of Oxford ([thesis](https://ora.ox.ac.uk/objects/uuid:c2b829f0-4810-416e-8e63-6919228c0722)).
Rule engines repeatedly derive new facts until nothing changes; I made this process faster, smaller in memory, and cheaper
to update when the input changes. The algorithms come with correctness proofs and were evaluated by integrating them into a commercial reasoning engine.
- *Optimised Storage for Datalog Reasoning*, AAAI 2024: compressed representations of derived data that still support
  incremental insertion and deletion, reducing memory by up to orders of magnitude.
  [[paper]](https://doi.org/10.1609/aaai.v38i9.28947) [[arXiv]](https://arxiv.org/abs/2312.11297) [[project page]](https://xinyuezhang.xyz/TCReasoning/) [[technical artifact]](https://github.com/verBubble/closure-tables)
- *Enhancing Datalog Reasoning with Hypertree Decompositions*, IJCAI 2023: structure-aware evaluation plans for recursive
  rules, often orders of magnitude faster on complex rules.
  [[paper]](https://www.ijcai.org/proceedings/2023/0377) [[arXiv]](https://arxiv.org/abs/2305.06854) [[project page]](https://xinyuezhang.xyz/HDReasoning/)
- *Open-source technical artifact*, [closure-tables](https://github.com/verBubble/closure-tables): a C++ implementation of
  dynamic transitive-closure and connected-component structures that report exactly what changed after each update,
  verified against brute force on thousands of randomised update sequences.

**Large-scale query log analysis**: undergraduate research, ISWC 2020.
Analysed massive real-world SPARQL query logs to model how users iteratively revise queries within a session.
[[paper]](https://arxiv.org/abs/2009.06625)
