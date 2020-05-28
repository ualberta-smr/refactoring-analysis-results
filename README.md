[![DOI](https://zenodo.org/badge/158746475.svg)](https://zenodo.org/badge/latestdoi/158746475)

# Refactoring Analysis Results
This repository contains the result of running the [refactoring analysis](https://github.com/ualberta-smr/RefactoringsInMergeCommits) used in our SANER '19 paper titled "Are Refactorings to Blame? An Empirical Study of Refactorings in Merge Conflicts" by Mehran Mahmoudi, Sarah Nadi, and Nikolaos Tsantalis.

### refactoring_analysis_dump_5_OCT_2018.sql.zip
This is a sql dump of the database.

### database.properties	
This file contains the database credentials.

### stats
There are two Python scripts in the [stats](stats) folder.
 - [data_resolver.py](stats/data_resolver.py): This script will print a summary of stats, including total number of merge scenarios, merge scenarios with involved refacotirngs, conflicting regions with involved refactorings, etc.
 - [plotter.py](stats/plotter.py): This script can draw a number of different plots.
