# Two dimentional Color images

- GEMINI is also used for color images within QBIC (Query By Image Content) project by IBM.
- this project studies methods to query large online images database using the image as a query.
- example of the content include color, texture, shape and dominant edges of images.

- for color we compute a k-element color histogram for each scene or item where k = 256 or 64 colors.
- each component in the histogram is the percentage of lixers that are most similar to that.

- d^2(hist) = sum [ a(ij) (xi - yi) (xj - yj) ]

- there are two obstacle for using GEMINI Method in Color Indexing
    - Dimensionality Curse.
    - Quardratic nature of distance function.

- to compute the distance between x^-> and q^-> then, we are not only going to compare bright red component of  x^-> to bright red component of q^-> but also other colors in the histogram.

- to resolve cross talk problem, use gemini approach for color images -:
    - step 1 -: find the distance between two color images. here D() = Dhist()
    - step 2 -: find one or more numerical features whose euclidean distance would lower bound Dhist()
    - feature extraction -:
        - the individual color pixel described by triplet (R,G,B).
        - so average of each pixel Ravg = (1/P) sum(R(p)) ....
        - so Davg(x, y) = (x - y)t (x-y).
    - The third step of the GEMINI algorithm is to prove that our simplified distance Davg() lower bound of that Dhist()