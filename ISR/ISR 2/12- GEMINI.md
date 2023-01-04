# GEMINI

- Several steps in GEMINI
    1. Determine the Distance D() between two objects
        - if each object is having f number of features then it can be represented in f- dimensional graph 
        O1(f1,f2,f3...ff)
        O2(f1,f2,f3...ff)
        O3(f1,f2,f3...ff)
        On(f1,f2,f3...ff)
        - query object is also represented int he same dimensional space
        - now distace between objects represent dis-similarity values (more far- more dis-similar)
        - denoted by D(O1, O2)
    2. Numerical Functions
        - find one or more numerical feature-extraction functions, to provide a ' quick and dirty test ' test.
        - if there are so many features then finding the distance will be hard so we need to reduce features, therefore we use numerical functions

    3. Prove that the distance in feature space is lower than the actual distance D(), to guarrantee correctness
        - D(F(O1), F(O2)) <= D(O1, O2)
        - if this condition doesn't hold true then it means something is wrong

    4. Use a Sptial Access method (like R-tree) to store and retrieve F-D feature vectors. 