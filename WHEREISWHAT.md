This should be a list of the main directories and what you SHOULD expect to find inside :

## dependent
Contains the very first demo build of QVIS, which will be focused on UI and less on what happens inside : as a matter of fact, it's a GUI running QGIS underneath. 

## base
Contains its own independent and stripped down version of the QGIS APIs, python and C++, kept as synchronised with the original ones, but withouth the map-exclusive features, so it is overall lighter if you aren't a cartographer and don't use QGIS. For compatibility reasons, the software will default to those even when QGIS is also installed, BUT you will be able to toggle the "map mode" inside of the app if QGIS is detected, which will both enable all the cool Layout Mode features from QGIS in QVIS, and make QVIS use the original QGIS APIs to deal with data live synced with a QGIS project.

## apis
Contains the QVIS exclusive APIs (or rather "exclusive" since of course you'll be able to reuse and modify them almost as you wish, see the GNU GPL2+ licence attached), which aren't found in QGIS and will try to fill the gap between what base QGIS can provide and what Adobe Illustrator and others provide.

## gui
Self explanatory I guess : contains the graphical user interface components

## notcode
Contains all the ressources that aren't code : images, icons, textures, documentations, etc.

## misc
We'll prefer making new directories whenever it's big stuff which directly regards the app's internals. For things likes distro-specific files or such, this will avoid to display a big mess for newcomers browsing upon this utopian land (I hope they'll contribute to make it less utopian and more realistic !)

welp that's all folks I guess
