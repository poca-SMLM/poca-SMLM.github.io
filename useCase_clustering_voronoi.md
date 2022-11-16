* Open a localization dataset (for instance ***simulation_1.csv*** in the folder ***data***, check Section [Opening localization files](opening.md)).

<p align="center">
	<img src="./images/localizationTab.png" width="800">
</p>

* Create a Voronoi diagram (check Section on [Voronoi diagram](voronoi.md))

<p align="center">
	<img src="./images/useCase_voro_01.png" width="800">
</p>

* Change the density feature to a logarithmic distribution

<p align="center">
	<img src="./images/useCase_voro_02.png" width="800">
</p>

* Apply a density factor, in this case 2 (check the [SR-Tesseler paper](https://doi.org/10.1038/nmeth.3579) for more information). This factor may be different depending on your data. 

<p align="center">
	<img src="./images/useCase_voro_03.png" width="800">
</p>

* Localizations with a density higher than the threshold have been discarded. Nevertheless, it is currently not seen because the rendering of the original localizations have not been unselected. Go to the ***Localizations//Filtering/Display*** tab and click on the ***Toggle display*** button.

<p align="center">
	<img src="./images/useCase_voro_04.png" width="800">
</p>

* If the thresholding is fine, create objects and toggle the Voronoi rendering off.

<p align="center">
	<img src="./images/useCase_voro_05.png" width="800">
</p>

* Pick one object and magnify it (by double clicking on it)

<p align="center">
	<img src="./images/useCase_voro_06.png" width="800">
</p>

* Each object is represent by its localizations, its shape, its localizations that are part of its surface and an ellipsoid that represents the object size (for 3D objects). You can click on the corresponding buttons to toggle the renderings.

<p align="center">
	<img src="./images/useCase_voro_07.png" width="800">
</p>

* Save the objects' statistics.

<p align="center">
	<img src="./images/useCase_voro_08.png" width="800">
</p>

You can find the corresponding macro [here](./macros/macro_use_case_voronoi.txt).

[Back to main page](README.md)