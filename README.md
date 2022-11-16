# PoCA: Point Cloud Analyst

## Introduction
PoCA is a a powerful stand-alone software designed to ease the manipulation and quantification of multidimensional and multicolor SMLM point cloud data. It is built around a custom-made Open-GL-based rendering engine that provides full user interactive control of SMLM point cloud data, both for visualization and manipulation. It combines the strengths of both C++ and Python programming languages, providing access to efficient and optimized C++ computer graphics algorithms and Python ecosystem. It is designed for improving users and developers’ experience, by integrating a user-friendly GUI, a macro recorder, and the capability to execute Python code easily. PoCA is the result of a decade of developments and the legacy of SR-Tesseler and Coloc-Tesseler, software solutions that were swiftly adopted by the community.

<p align="center">
	<img src="./images/poca.gif" width="1000">
</p>

**If you use it, please cite it:**

* Florian Levet, Eric Hosy, Adel Kechkar, Corey Butler, Anne Beghin, Daniel Choquet, Jean-Baptiste Sibarita. 
*SR-Tesseler: a method to segment and quantify localization-based super-resolution microscopy data*. [Nature Methods 12 (11), 1065-71 (2015) doi:10.1038/nmeth.3579](https://doi.org/10.1038/nmeth.3579)

* Florian Levet, Guillaume Julien, Rémi Galland, Corey Butler, Anne Beghin, Anaël Chazeau, Philipp Hoess, Jonas Ries, Grégory Giannone, Jean-Baptiste Sibarita. 
*A tessellation-based colocalization analysis approach for single-molecule localization microscopy*.
[Nature Communications 10, 2379 (2019) doi:10.1038/s41467-019-10007-4](https://doi.org/10.1038/s41467-019-10007-4)

PoCA is developed by [Florian Levet](https://www.researchgate.net/profile/Florian-Levet), researcher in the [Quantitative Imaging of the Cell team](https://www.iins.u-bordeaux.fr/SIBARITA), headed by [Jean-Baptiste Sibarita](https://www.researchgate.net/profile/Jean-Baptiste-Sibarita). FL and JBS are part of the [Interdisciplinary Insitute for Neuroscience](https://www.iins.u-bordeaux.fr/). FL is part of the [Bordeaux Imaging Center](https://www.bic.u-bordeaux.fr/).

If you search for support, please open a thread on the [image.sc](https://image.sc/) forum or raise an [issue](https://github.com/flevet/PoCA/issues) here.

## Overview
* [Installation and compilation](installation.md)
* [PoCA main interface](./images/poca_windows.png)
* [Opening localization files](opening.md)
* [Manipulating point clouds](manipulating.md)
	- [Visualization](manipulating.md#visualization)
	- [Filtering](manipulating.md#filtering)
	- [Cropping](manipulating.md#cropping)
	- [Picking](manipulating.md#picking)
* Quantification techniques
	- [Delaunay triangulation](delaunay.md)
	- [Voronoi diagram](voronoi.md)
	- [DBSCAN](dbscan.md)
* [Objects](objects.md)
* Colocalization analysis
	- [Prerequesite](prerequesite_coloc.md)
	- [Coloc-Tesseler](coloc-tesseler.md)
	- [Object colocalization](objects_colocalization.md)
* [ROIs](rois.md)
* [Macros](macros.md)
* [Executing Python scripts](python.md)
* [How to cite](citations.md)


## Use cases
* [Creation of clusters with a Voronoi diagram](useCase_clustering_voronoi.md)
* [Creation of clusters with a Delaunay triangulation](useCase_clustering_delaunay.md)
* [Colocalization analysis with Coloc-Tesseler](useCase_coloc_tess.md)
* [Colocalization analysis with object colocalization](useCase_coloc_objs.md)