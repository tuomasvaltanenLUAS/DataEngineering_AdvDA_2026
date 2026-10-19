In this folder, we have examples that help 
us with distribution and overlap management.

The tasks will include undersampling, oversampling/data synthetization 
and overlap management tools.

This includes:

Undersampling:
    - Random under sampling
    - ClusterCentroids
    - ENN (Edited Nearest Neighbors) (extra)

Data synthetization / oversampling:
     - SMOTE (usually used with classification)

     - SDV (also support conditions)
        - CTGAN
        - CopulaSynthesizer
        - TVAE (Tabular Variable Autoencoder)

    - Other optional/extra approaches:
        - GMM (Gaussian Mixture Models)
        - Duplicate + noise generation
        - ADASYN

    - Special case: TabFairGAN (optional: for sensitive/human-oriented data)

Overlap management:
    - TomekLinks
        - Even SmoteTomek exists (combination of SMOTE + TomekLinks)

    - ClusterCentroids
    - Clustering (KMeans etc.) (optional, but powerful)
        - Example on this will be shown later with the red wine dataset optimization
    - Autoencoders (optional)

Other tools:
    - Smart imputation features (scikit-learn)

Needed installations (some of these take time):
-----------------------------------------------

pip install imblearn
pip install ctgan 
pip install sdv
pip install tabfairgan

