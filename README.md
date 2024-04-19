# Voigt fitting


## Description
Labspec software, as far as I know, still has a bug when saving mapping data under raster images in high-quality export. Nevertheless, it is always possible to save the table of data in text format. Via this project, I created a solution to open this mapping data under different tunable color maps. 
A visual interface, as well as a notebook file solution, are available for direct use.

<img src="preview_gui_nb.png" alt="screenshot_app.png" style="width:900px;height:200px;"> 

The graphical interface allows a direct presentation of the map data after a loading of the txt file. The first notebook allows a plotting of the mapping in normal or binary mode. The second one allows the combination of two maps by performing arithmetic operations. This can be very useful to highlight the wanted information vis-à-vis the contribution of different peaks.

## Installation
To run the main file or the notebook files, I recommend to setup a python virtual environment (tested and verified under 3.8.0 version) and adding the required libraries using the following command after cloning/downloading the rep :
```console
pip install -r requirements.txt
```
## Usage
The use of the graphical interface, as well as the notebook files, is super user-friendly; 
<br>For the notebook version, you have to add the voigt functions. You run the cell and keep adjusting them manually. When you are saving the data, they will be named voigt 1, voigt 2, etc (there is no limit fot the functions number).
<br>For the Qt version, you will do basically the same using the available butons.



## Roadmap
 <ul>
  <li>Perform arithmetic operations in the graphical interface</li>
  <li>More coloring options (gamma, etc)</li>
  <li>Add segmentation, second derivative options, etc</li>
  <li>Transform the project on a desktop application</li>
</ul> 

## Support and Contributing
Let me know if you have any suggestions/ideas to enhance those scripts or add further settings. Your suggestions are warmly welcomed.
<br>
In case of a problem, It is strongly recommended to post an issue. For a more confidential demand, don't hesitate to email me.


