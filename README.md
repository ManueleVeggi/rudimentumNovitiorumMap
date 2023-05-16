# The <i>Rudimentum Novitiorum</i> Map 

Immersive environment based on the world map printed in the "Rudimentum Novitiorum" (1475). <br> Project of developed as Visiting student at [EPFL - eM+](https://www.epfl.ch/labs/emplus/). <br> Used software: **Unreal Engine 5.1**

## The project

The project is a prototype of a design proposal elaborated by Khajehnouri Shayan, Daghfal Mariella and Tang Cindy in the framework of the course [Cultural Data Sculpting](https://edu.epfl.ch/coursebook/en/cultural-data-sculpting-DH-404), held by Prof Kenderdine for the MSc in "Digital Humanities" at EPFL.

It consists of an immersive and interactive environment for Panorama+ Visualization System based on the map contained in the "Rudimentum Novitiorum" (1475):
<p align="center"> <img src="https://upload.wikimedia.org/wikipedia/commons/5/54/1475_Rudimentum_Novitorum_Lucas_brandis.jpg" style="width: 50%"> </p>

Developed in Unreal Engine 5.1, it reproduces a part of the world (the landscape now corresponds to Asia, even though onlz the upper right quarter of the map has been populated) and provides a sample of animation (sample scenario: Ophir) based on the text of the manuscript.


<!-- <p align="center"> <img src="RudNovMap/Saved/Screenshots/WindowsEditor/ScreenShot00000.png" style="width: 50%"> </p> -->

### Roadmap

| **Week**                  | **Tasks**                                                                                                                                                                                                                                                                    |
|---------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 21st - 28th April 2023    | _Creation of the landscape_ <br> 1) Definition of the heightmap on Gimp, application of blur and erosion with Gaea <br> 2) Refinement and paint with Unreal "Landscape" Mode <br> 3) Population of the environment with material and assets downloaded on QuixelBridge and UE Marketplace |
| 28th April - 4th May 2023 | _Definition of the animation of the lions in the Golden Land of Ophir_ <br> 1) Animation Blueprint: creation of the animation graph (with use of blendspace) <br> 2) Definition of the actors behavior in the Blueprint Event Graph <br> 3) Use of Level blueprint to control trigger boxes |
| 5th - 11th May 2023       | Refinement of the landscape <br> _Creation of compass bar_ <br> 1) Creation of the texture and of the interactive Widget Blueprint <br> 2) Real-time update of the marker icon|
| 12th - 18th May 2023 <br> 19th - 25th May 2023       | Refinements and adjustments <br> 1) Place name labels <br> 2) Camera effects <br> 3) Textures and material adjustments|
