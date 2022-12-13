# Graphical Convex Hull

The graphical convex hull uses WebGL, JavaScript, and HTML to render a convex hull. Random vertices are generated to create points, which are then rendered. The points are then sorted by their x values. Now that the left-most point can be determined, an algorithm is used to determine the next left-most point. This process iterates until the next left-most point is the original left-most point. The values of each left-most point are then used to render lines, creating the convex hull.
