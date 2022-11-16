* Open a localization dataset (for instance ***simulation_1.csv*** in the folder ***data***, check Section [Opening localization files](opening.md)).

<p align="center">
	<img src="./images/localizationTab.png" width="800">
</p>

* Create a Delaunay triangulation (check Section on [Delaunay triangulation](delaunay.md))

<p align="center">
	<img src="./images/useCase_delau_01.png" width="800">
</p>

* When rendering the Delaunay triangulation, please make sure that the ***Cull face*** is not selected. Culling is an OpenGL process that will not rendering some triangles depending on their orientation. When on, it may seem like some tetrahedra were not computed.

<p align="center">
	<img src="./images/useCase_delau_02.png" width="800">
</p>

* Chnage the volume feature to logarithmic distribution and toggle off the rendering of the localizations (check the [Voronoi use case](useCase_clustering_voronoi.md) for more information). Then apply a cutting distance, in this case 45 nm. This distance may be different depending on your data. 

<p align="center">
	<img src="./images/useCase_delau_03.png" width="800">
</p>

* If the thresholding is fine, create objects and toggle the Delaunay rendering off.

<p align="center">
	<img src="./images/useCase_delau_04.png" width="800">
</p>

* Save the objects' statistics.

<p align="center">
	<img src="./images/useCase_voro_08.png" width="800">
</p>

You can find the corresponding macro [here](./macros/macro_use_case_delaunay.txt).

[Back to main page](README.md)