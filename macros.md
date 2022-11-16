PoCA supports macros for automatizing the analysis of point clouds, with all macros being saved as ***json*** files (with the txt extension). A ***Macro*** tab is available with a ***Recorder*** and a ***Runner***. All commands performed in PoCA are recorded in the recorder. 

<p align="center">
	<img src="./images/macroTab.png" width="1000">
</p>

### Recorder

<p align="left">
	<img src="./images/macroRecorder.png" width="500">
</p>

<img align="left" src="./images/macroRecorder_transfer.png" height="25">&ensp;Transfer all the recorded commands to the runner.

<img align="left" src="./images/macroRecorder_clipboard.png" height="25">&ensp;Transfer all the recorded commands to the clipboard.

<img align="left" src="./images/macroRecorder_save.png" height="25">&ensp;Save all the recorded commands to a json file.

If the user opens a localization dataset (csv file).
<p align="center">
	<img src="./images/macroRecorder_01.png" width="1000">
</p>

<p align="center">
	<img src="./images/macroRecorder_02.png" width="800">
</p>

The corresponding command is recorded.

<p align="left">
	<img src="./images/macroRecorder_03.png" width="500">
</p>

The command contains the filename, the calibration, the separator (44 is the ASCII value for ***,***) and the name and position of all the read columns.

This simple macro can be transferred to the runner by clicking on ***Transfer to runner***.

### Runner

<p align="left">
	<img src="./images/macroRecorder_04.png" width="500">
</p>

<img align="left" src="./images/macroRecorder_05.png" height="25">&ensp;Load a macro in the runner.

<img align="left" src="./images/macroRecorder_06.png" height="25">&ensp;Save the macro that is currently in the runner textbox.

<img align="left" src="./images/macroRecorder_07.png" height="25">&ensp;Execute the macro that is currently in the runner textbox.


Modifying the ***path*** parameter of the command to ***simulation_2.csv***, and clicking on ***Run*** will open the localization dataset ***simulation_2.csv***.

When a complete macro is defined, you can apply it to another localization dataset or to a full directory with these buttons. Beware: the macro requires to have as first command ***MainWindow//open*** as it will define how to read the csv files. 

<img align="left" src="./images/openFile_icon.png" height="25">&ensp;Apply the macro to the chosen localization file.

<img align="left" src="./images/openDir_icon.png" height="25">&ensp;Apply the macro to localization files that are in the chosen folder.

[Back to main page](README.md)