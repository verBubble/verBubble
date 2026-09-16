### Hi, I'm Xinyue Zhang 👋

DPhil in Computer Science at the University of Oxford.
I design algorithms for complex reasoning systems, prove them correct, and build and evaluate them at scale.
The same questions run through this work: how to keep a system's conclusions correct and consistent as its inputs change,
and how to make large-scale automated reasoning efficient enough to use in practice, which matters wherever software must
derive trustworthy conclusions, from program analysis and knowledge graphs to reliable, verifiable reasoning in AI systems.
[Google Scholar](https://scholar.google.com/citations?user=HrDe_SkAAAAJ&hl=en)

### Selected Research

**Efficient and reliable automated reasoning**: PhD research, University of Oxford ([thesis](https://ora.ox.ac.uk/objects/uuid:c2b829f0-4810-416e-8e63-6919228c0722)).
Rule-based reasoning systems derive new conclusions from data, but on large, constantly changing data this is slow,
memory-hungry, and expensive to redo. I designed algorithms that make it faster, far more compact, and cheap to keep
up to date, proved them correct, and evaluated them inside a commercial reasoning engine (up to 123× less memory and 124× faster).
- *Optimised Storage for Datalog Reasoning*, AAAI 2024: a compressed representation of reachability in large graphs
  that supports insertions and deletions and reports exactly which conclusions changed after each update.
  [[paper]](https://doi.org/10.1609/aaai.v38i9.28947) [[arXiv]](https://arxiv.org/abs/2312.11297) [[project page]](https://xinyuezhang.xyz/TCReasoning/) [[technical artifact]](https://github.com/verBubble/closure-tables)
- *Enhancing Datalog Reasoning with Hypertree Decompositions*, IJCAI 2023: evaluates complex recursive rules by breaking
  them into tree-shaped pieces, avoiding redundant work, including when the data is updated incrementally.
  [[paper]](https://www.ijcai.org/proceedings/2023/0377) [[arXiv]](https://arxiv.org/abs/2305.06854) [[project page]](https://xinyuezhang.xyz/HDReasoning/)
- *Open-source technical artifact*, [closure-tables](https://github.com/verBubble/closure-tables): a tested C++ implementation
  of the core data structures, verified by randomised differential testing against brute force on thousands of update sequences.

**Empirical analysis of user behaviour at scale**: undergraduate research, ISWC 2020.
Analysed massive real-world query logs: separated automated (bot) traffic from human behaviour and modelled
how users' intent shifts across a session with Hidden Markov Models.
[[paper]](https://arxiv.org/abs/2009.06625)
