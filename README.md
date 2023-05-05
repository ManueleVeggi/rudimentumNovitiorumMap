# The <i>Rudimentum Novitiorum</i> Map 

Immersive environment based on the world map printed in the "Rudimentum Novitiorum" (1475). Project of developed as Visiting student at EPFL - eM+. Used software: Unreal Engine 5.1

## The project

The project is a prototype of a design proposal elaborated by Khajehnouri Shayan, Daghfal Mariella and Tang Cindy in the framework of the course [Cultural Data Sculpting](https://edu.epfl.ch/coursebook/en/cultural-data-sculpting-DH-404), held by Prof Kenderdine for the MSc in "Digital Humanities" at EPFL.

It consists of an immersive and interactive environment for Panorama+ Visualization System based on the map contained in the "Rudimentum Novitiorum" (1475):
<p align="center"> <img src="https://upload.wikimedia.org/wikipedia/commons/5/54/1475_Rudimentum_Novitorum_Lucas_brandis.jpg" style="width: 50%"> </p>

Developed in Unreal Engine 5.1, it reproduces a part of the world (the landscape now corresponds to Asia, but only the upper right quarter is refined and populated) and provides a sample of animation (sample scenario: Ophir).

Besides the actual development of the environment and of its actors´ behaviors, the project also required an analysis and translation of the original Latin manuscript. Indeed, every event happening in the digital map is a reconstruction of the stories described in the _Rudimentum_. 

### Roadmap

| **Week**                  | **Tasks**                                                                                                                                                                                                                                                                    |
|---------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 21st - 28th April 2023    | _Creation of the landscape_ <br> 1) Definition of the heightmap on Gimp, application of blur and erosion with Gaea <br> 2) Refinement and paint with Unreal "Landscape" Mode <br> 3) Population of the environment with material and assets downloaded on QuixelBridge and UE Marketplace |
| 28th April - 4th May 2023 | _Definition of the animation of the lions in the Golden Land of Ophir_ <br> 1) Animation Blueprint: creation of the animation graph (with use of blendspace) <br> 2) Definition of the actors behavior in the Blueprint Event Graph <br> 3) Use of Level blueprint to control trigger boxes |
| 5th May - ...             | _Creation of compass bar_ <br> 1) Creation of the texture and of the interactive Widget Blueprint|
