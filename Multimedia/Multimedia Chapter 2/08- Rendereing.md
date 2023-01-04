# Rendering Algorithms

- Rendering is the process of generating an image from a model by means of computer programs.
- Rendering is modtly used in architechtural design, video games, animated movies, simulators and design visualization.
- Techniques and features vary according to project.
- Rendering helps increase efficiency and reduce cost design.

- Two types of rendering -:
    - Pre-Rendering ->
        - used where speed is not the concern
        - image calculations are performed using multi-core central processing unit.
        - mostly used in animation and visual effects
    - Real-Time Rendering -> 
        - technique used in interactive graphics and gaming where images must be created at rapid pace.
        - Because user interaction is high in this case so real time rendering is required.
        - dedicated graphics hardware has improved the performance of real-time rendering.

- Four Techniques of Rendering -:
    - Scan Line -:
        - it works on a row by row basis without any advanced optical effects.
        - Geometrically projects.
        - objects in the scene to an image plane.

    - Ray Casting -:
        - observe a view from a specific point of view.
        - calculate the observed image based only on geometry and very basic optical laws of reflection intensity.
        - perhaps using monty carlo techniques to reduce artifacts.

    - Radiosity -:
        - not usually implemented as a rendering technique
        - but instead calculate the passage of the light as it leaves the light source and illuminates surfaces.
        - these surfaces are usually rendered to the display using one of the three techniques.

    - Ray Tracing -:
        - similar to ray casting, but employs more advanced optical simulation
        - usually uses monte carlo technique to obtain more realistic results at a speed that is often orders of magnitude faster.
