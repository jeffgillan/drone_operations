# drone_operations


Mavic 3 Enterprise

* On one battery, the M3E can map **~1 sqkm**, at 120 m AGL, speed of 15 m/s, 80% forward overlap, 70% side overlap, nadir, single grid. It takes about 28 flight minutes. You would need 2 batteries to ensure completion. For orthomosaic missions, I should fly a double grid.

* At max flyin height I can collect imagery over ~2 sq km per day. This is 200 hectares or ~500 acres. 

* When deleting images on the microSD card, move the images to the trash, then empty the trash. Otherwise, images are not deleted.

* Bring an external power source for the remote controller. 

<br>
<br>
<br>

## Macbook Air Software Stack
* Agisoft Metashape GUI and python module
* Cloudcompare GUI
* QGIS GUI
* Docker desktop and CLI tool
* exiftool CLI tool
* VS Code
* WebODM

  `cd /users/jgillan/Documents/repositories/WebODM`

  `./webodm.sh start`
