Multicollinearity and redundancy:

- Use also your own thinking to decide these (MOST IMPORTANT!)
    some of these can be quite self-explanatory, e.g. multiple variables 
    containing square footage (almost identical information) etc.

Common tools:

- VIF test
- Correlation matrix / phik-matrix 
    (see also y-data -example in task1a_1d -> task4d_alternatives_extra -folder!)

- For correlation/phik-matrix, consider also these tools:
    - SweetViz "associations" tool 
    - Dython -approach (see example)

- RFE (recursive feature elimination) (to some extent)

- Mutual Information (it's a method) can be also used to help (like RFE)

To some extent, also Fisher score and SelectKBest can be helpful (look for variables with low scores).