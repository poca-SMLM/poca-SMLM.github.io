After loading a CSV file, a new window opens with the point cloud displayed. The ***Filtering/Display*** tab in the ***Localizations*** tab allows to filter features and change the point cloud visualization mode.

## Visualization

<p align="center">
	<img src="./images/localizationTab.png" width="800">
</p>

In the ***Filtering*** section, we have:

<p align="left">
	<img src="./images/LUTs.png" width="250">
</p>

These buttons allows to change the LUT applied to the chosen ***feature***.

<p align="center">
	<img src="./images/lut_changed.png" width="800">
</p>

The LUT was changed from ***HotCold*** to ***Ice***.

<p align="left">
	<img src="./images/buttonsLocs.png" width="250">
</p>

These buttons allows several actions:

<img align="left" src="./images/save_icon.png" height="25">&ensp;Save all the localizations with their features.

<img align="left" src="./images/point_rendering_icon.png" height="25">&ensp;Select the point rendering.

<img align="left" src="./images/heatmap_rendering_icon.png" height="25">&ensp;Select the heatmap rendering.

<p align="center">
	<img src="./images/heatmap.png" width="800">
</p>

The heatmap rendering project all the localization to the screen and compute a kind of density. As this is done during the rendering step, in the graphics card, this rendering is not quantitative. Parameters to this rendering are available in the ***Heatmap*** section.

<img align="left" src="./images/gaussian_rendering_icon.png" height="25">&ensp;Select the Gaussian rendering.

<p align="center">
	<img src="./images/gaussian_rendering.png" width="800">
</p>

The Gaussian rendering renders the points as Gaussian, in 2D or 3D. It works better with a black background since it requires alpha blending. Parameters are available in the ***Gaussian*** section.

<img align="left" src="./images/rendering_icon.png" height="25">&ensp;Toggle the localization rendering.

<img align="left" src="./images/size_points.png" height="25">&ensp;Define the size of the point to be redering when the point or Gaussian rendering are selected.

## Filtering

<p align="center">
	<img src="./images/histogram.png" width="800">
</p>

Each feature is represented as an histogram that can be filtered, either by changed the minimum and maximum in the textboxes, or bien clicking on the histogram (left button for changing the minimum, right button for changing the maximum). The ***target*** icon is used to select this feature for applying the LUT on the localizations. The **floppy disk*** is used to save the whole distribution of this feature. The ***checkbox*** is used to convert the feature to a log distribution.

<p align="center">
	<img src="./images/poca_filter.gif" width="1000">
</p>

<img align="left" src="./images/duplicate.png" height="25">&ensp;This button duplicate a localization dataset with the current filtering. It is available in the PoCA toolbar.


## Cropping

3D point clouds can be cropped to facilitate manipulation and exploration. The buttons are avilable in the PoCA toolbar.

<img align="left" src="./images/crop.png" height="25">&ensp;Toggle cropping. It requires to have first selected the XY, XZ or YZ frame rotation.

<img align="left" src="./images/xy.png" height="25">&ensp;Rotate the point cloud to the XY frame.

<img align="left" src="./images/xz.png" height="25">&ensp;Rotate the point cloud to the XZ frame.

<img align="left" src="./images/yz.png" height="25">&ensp;Rotate the point cloud to the YZ frame.

<p align="center">
	<img src="./images/poca_crop.gif" width="1000">
</p>

After clicking on the ***crop*** icon, you just have to perform the crop on the point cloud by pressing the left mouse button, moving the crop selection to the desired end and releasing the mouse button.


## Picking

As seen in the Gifs above, when the mouse passes on elements (localizations, objects, etc...), informations about those elements are displayed in a yellow box, directly on the screen. All the features of the elements are displayed.

[Back to main page](README.md)