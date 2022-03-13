### chem 96 final project (14 March 2022, prof robustelli):
# IDP molecular dynamics trajectory clustering

The files in this folder elaborate three approaches (two via Jupyter Notebooks, one from the command line) to MD clustering. The model system is the intrinsically disordered n-terminal domain of the measles virus nucleoprotein&mdash;all relevant trajectory/topology files supplied by Prof Robustelli and not necessarily committed here.

While TTClust (with a command-line UI) is perhaps the most flexible, user-friendly, robust, and easily manipulatable approach of these three, it can be worthwhile to run the necessary code oneself. As for the implementations, K-means seems to be fairly consistent and to yield clusters of appropriately low-energy conformations. But DBSCAN focuses so strongly on probability density (and thus free energy) that, while its clusters look a little exaggerated compared to those from hierarchical methods, it's most likely more useful for studying helical and other highly-structured conformation clusters.

__See the `results` folders for:__
1) renderings of cluster centers/"leaders" from VMD
2) radius of gyration probability distribution plots
3) RMSD from fully helical conformation histograms
4) helix/sheet secondary structure propensity

__See the main folder for:__
1) the Jupyter notebook delineating all computations and analyses
2) presentation slides introducing the concept and preliminary results
