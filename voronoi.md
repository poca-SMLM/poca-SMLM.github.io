<p align="center">
	<img src="./images/poca_voronoi.gif" width="1000">
</p>

<img align="left" src="./images/voronoi_icon.png" height="25">&ensp;Clicking the ***Voronoi*** icon in the PoCA toolbar will create a Voronoi diagram of the point cloud, automatically determining if it has to be in 2D or 3D. 

During the construction of the Voronoi diagram, two features are computed: a surface (2D point clouds) or a volume (3D point clouds) feature and a density feature (please refer to the original [SR-Tesseler](https://doi.org/10.1038/nmeth.3579) paper for more explanations). These features can be filtered by the histograms.

List of actions available:

<img align="left" src="./images/invert_icon.png" height="25">&ensp;Invert selection.

<img align="left" src="./images/bbox_icon.png" height="25">&ensp;Toggle rendering of the bounding box of the picked polygon/polyhedron.

<img align="left" src="./images/create_objects_icon.png" height="25">&ensp;Create objects with the current triangles/tetrahedra selected.

<img align="left" src="./images/point_rendering_icon.png" height="25">&ensp;Toggle rendering of point colored with the Voronoi LUT and feature selected.

<img align="left" src="./images/polygon_icon.png" height="25">&ensp;Toggle rendering of the polygons/polyhedra.

<img align="left" src="./images/fill_icon.png" height="25">&ensp;Fill or not the surface of the polygons/polyhedra.

<img align="left" src="./images/rendering_icon.png" height="25">&ensp;Toggle rendering of the Voronoi diagram.

<p align="left">
	<img src="./images/parameters_voronoi.png" width="600">
</p>

When using the Voronoi diagram the segmentation can be performed by filtering the feature histogram, applying a cutting distance or applying a density factor (please refer to the original [SR-Tesseler](https://doi.org/10.1038/nmeth.3579) paper for more explanations). Parameters for the creation of objects are available in the section shown above.

The ***Characteristics*** section implements an upgrade of the [ClusterVisu](https://doi.org/10.1038/srep24084) technique and is under development.

<p align="center">
	<img src="./images/clustervisu.png" width="500">
</p>

[Back to main page](README.md)