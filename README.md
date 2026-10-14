# GLRMask: Constrained Decoding with Boolean Array Weighted Automata

**Isaac Breen · HTML research preprint · Version 1 · 9 October 2026 · reading edition revised 14 October 2026**

[**Read the paper (HTML)**](https://isaacbreen.github.io/glrmask-preprint/)

This is an independently authored research preprint presenting a weighted-automaton approach to grammar-constrained decoding. It is **not peer reviewed**.

The readable HTML includes MathJax-rendered equations, figures, navigation, and the bibliography. The optional [annotated HTML](https://isaacbreen.github.io/glrmask-preprint/current.html) adds paragraph and sentence labels for review.

The current evaluation uses the retained 14 October 2026 native AWS run. JSON headline TBM uses 11,277 complete valid trajectories accepted by all four engines (1,734,930 positions per engine); TTFM uses 8,326 common-built schemas. Practical JavaScript headline TBM uses 28 complete valid trajectories (3,805 positions); its 55 cold-build cases share one grammar, and only 51 fixtures are correctly evaluated by all engines.

The run has one wall-clock pass without CPU pinning or SMT sibling reservation, and checkpoint publication overlapped timing. Saved telemetry cannot isolate scheduling effects. All raw failures and historical measurements remain preserved; these selected cohorts do not establish whole-language equivalence or whole-corpus dominance. The [PDF edition](publication-review.pdf) and HTML are generated from the same authored source. Related work, including PSC, is discussed in Section 11.

This repository archives the public HTML edition. The GLRMask implementation is at [IsaacBreen/glrmask](https://github.com/IsaacBreen/glrmask).

All rights reserved unless otherwise indicated; making this paper publicly readable does not imply an open-content license.
