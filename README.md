# Files to be prepared
- Raw csv files, available in [MyCore](https://mycore.core-cloud.net/index.php/s/tFSrR5f7ZkVFwj7/authenticate), folder `Résultats/MigrationRessources/VersionReformateePlateforme_SansSemantique`. Put all csv in `raw_csv_files` folder.
- [AOCPosetBuilder.jar](https://www.lirmm.fr/~gutierre/gsh), a Java file for building AOC poset
- frequencies-frcowvec.csv, words from COW and their frequency
- glawinette-series.csv
- [lemma-A-pos-bow.txt](https://zenodo.org/record/5975226), distribution vector of words, for calculating cosine similarity

# Software requirements
- [NetworkX](https://networkx.org/), Python package for graph manipulation
- [Graphviz](https://graphviz.org/) for visualizing .dot files