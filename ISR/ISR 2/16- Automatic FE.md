# Automatic Feature Extraction

- GEMINI is useful for the setting from which we can extract features
- Use of class label in feature extraction is called Un. Sup. FE
- otherwise it is called Sup. FE.

- There are two main Automatic Extraction methods-:

  - multidimensional scaling (MDS) -:

    - non linear feature extraction.
    - used to lower the dimentionality from high dimensional space to lower dimensional space
    - the distances between the samples in the original space are preserved, as much as possible in the reduced phase.
    - if distance is calculated according to metric measurement, called metric MDS.

  - FastMap -:
    - it is an algorithm to map objects into points in some k-dimensional space, such that the similarities are preserved.
    - It can calculate plotting position with existing distance calculation method.
    - therefore more convinient in graphing the document space.
    - linear in nature, therefore faster than MDS.
