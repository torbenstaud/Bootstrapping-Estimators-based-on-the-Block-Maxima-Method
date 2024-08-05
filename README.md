# Bootstrapping-Estimators-based-on-the-Block-Maxima-Method

**NOTIZEN FÜR DICH SELBST**

-   fixed r: mean und Fréchet

-   fixed n: Fréchet

    -   bst DONE

    -   est DONE

    -   Auswertung fehlt!

-   Runtime Comparison: DONE

-   case Study: DONE

-   Anleitung, wie das zu nutzen ist: Auch wie das Projekt geht

    -   Sourcen im HPC ansprechen und in Files schreiben, was gesourced werden muss

**NOTIZEN ENDE**

This repository contains the code used to generate the simulation and case studies of the paper: Bücher, Staud (2024): Bootstrapping Estimators based on the Block Maxima Method.

The structure is as follows:

-   **src**: Contains both the R- and Rcpp source code for the simulation study

-   **data**: Contains data generated by scripts of processing nature. **Attention**: raw data generated by the HPC is not uploaded as it would exceed the data storage capacity.

-   **results**: Contains the various plots produced.

-   **scripts**: Contains the various scripts used to generate/process data and plots.

    -   subfolders indicate simulation sub-studies which needed computational power aided by a High Performance Cluster (HPC) (provided by *ZIM: Heinrich-Heine University Dusseldorf*; for which we are grateful)
