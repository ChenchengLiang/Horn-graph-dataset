# Horn-graph-dataset
Horn-graph-dataset for five proxy tasks.


For one program verification problem, we have the following corresponding files:

• Original SMT-LIB file from a collection of benchmarks in CHC-COMP [1].

• Simplified SMT-LIB file by preprocessing [2].

• Normalized SMT-LIB file by normalization.

• *.hyperedge.gv file: written in DOT language [3], and can be rendered to visualization
format such as jpg for the CDHG.

• *.hyperedge.JSON file: include all node, edge, and corresponding label information for
the CDHG, and is the input of the R-HyGNN model.

• *.layerHornGraph.gv: written in DOT language, and can be rendered to visualization
format such as jpg for a constraint graph.

• *.layerHornGraph.JSON file: include all node, edge, and corresponding label information
for the constraint graph, and is the input for the R-HyGNN model.


Notice that the simplified and normalized SMT-LIB files are logically equivalent to the original
SMT-LIB file. The constraint graph is constructed from the simplified SMT-LIB files, while the
CDHG is constructed from the normalized SMT-LIB files.



[1] G. Fedyukovich, P. Rümmer, Competition report: CHC-COMP-21, 2021. URL: https://chc-
comp.github.io/2021/report.pdf.


[2] H. Hojjat, P. Ruemmer, The ELDARICA Horn solver, in: 2018 Formal Methods in Computer
Aided Design (FMCAD), 2018, pp. 1–7. doi:10.23919/FMCAD.2018.8603013.

[3] E. R. Gansner, E. Koutsofios, S. North, Drawing graphs with dot, 2015. URL: https://
www.graphviz.org/pdf/dotguide.pdf.
