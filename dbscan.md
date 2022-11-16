An optimized implementation of [DBSCAN](https://www.aaai.org/Papers/KDD/1996/KDD96-037.pdf) is available in the ***Localizations//DBSCAN*** tabs.

<p align="center">
	<img src="./images/dbscanTabs.png" width="1000">
</p>

DBSCAN uses two main parameters to cluster: a ***distance*** used to compute the localizations' density (designed as ***Eps-neighborhood*** in the original paper) and a ***minimum number of points*** in this distance to classify localizations as core points (***MinPts*** in the original paper).

<p align="left">
	<img src="./images/dbscan_parameters.png" width="500">
</p>

When you click on the ***DBScan*** button, PoCA will compute the clustering with the current parameters. PoCA then compute the size of the different objects and display the results in a table and in an histogram. Beware: objects are not internally stored by PoCA. You need to create them explicit after through the appropriate button to have access to them in the ***ObjectList*** tab.

<p align="center">
	<img src="./images/dbscan_segmentation.png" width="1000">
</p>

<img align="left" src="./images/create_objects_icon.png" height="25">&ensp;Create objects with the current triangles/tetrahedra selected.

<img align="left" src="./images/rendering_icon.png" height="25">&ensp;Toggle rendering of the DBSCAN result.

[Back to main page](README.md)