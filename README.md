# Information Content Field Weighting (ICFW) for Structured Document Retrieval
A repository detailing the ICFW models described in T .Ketola & T. Roelleke, Automatic and Analytical Field Weighting for Structured Document Retrieval, 2023.

## Content
As the experimentation is based on external datasets (DBpedia, Trec-small-web, HomeDepot) the full experimentaion cannot be run without preprocessing of the data.

The data folder contains examples of .json files which are used for re-ranking by the jupyter notebook.

non-optimised-models.ipynb contains the functions and running scripts for the non-optimised task.

optimised-models.ipynb containts the functions required for optimising the two supervised ICFW models. Currently the repository does not contain the functions required for the coordinate ascent optimisation, but their implementation should be relatively straight forward given the paper and the functions in optimised-models.ipynb.

## Support
Do not hesitate to contact me here on any issues regarding the running of the scripts, implementation or anything else.
