* Open 2 localization datasets (for instance ***simulation_1.csv*** and ***simulation_2.csv***) in the ***data*** folder.

<p align="center">
	<img src="./images/useCase_colocTess_01.png" width="800">
</p>

* Create a colocalization dataset.

<p align="center">
	<img src="./images/useCase_colocTess_02.png" width="800">
</p>

* Compute the ***Coloc-Tesseler*** method (check the [paper](https://doi.org/10.1038/s41467-019-10007-4)).

<p align="center">
	<img src="./images/useCase_colocTess_03.png" width="800">
</p>

* While a ***Colocalization*** tab has been created, we cannot see the classification of Coloc-Tesseler. This is due to the fact that the localizations rendering is still on. We need to toggle it off. Go to the ***Localizations//Filtering/Display*** tabs and use the ***Toggle display*** button. Use the ***1*** and ***2*** buttons to switch between the two colors.

<p align="center">
	<img src="./images/useCase_colocTess_04.png" width="800">
</p>

* All the localizations are black because no threshold was set. Go to the ***Colocalization//Coloc-Tesseler*** tabs. Apply factors of 1 and 1 for the two colors (clicking on the scatterplot will automatically change these thresholds). Click on ***Apply***.

<p align="center">
	<img src="./images/useCase_colocTess_05.png" width="800">
</p>

* This has computed the Spearmann and Manders coefficients, and classified all the localizations. Results can be exported by clicking on the **Floppy disk*** button.

<p align="center">
	<img src="./images/useCase_colocTess_06.png" width="500">
</p>

You can find the corresponding macro [here](./macros/macro_use_case_coloc_tesseler.txt).

[Back to main page](README.md)