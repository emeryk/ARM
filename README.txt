This README file describes the ARM Project 2017 release.
This project was carried out for the EU : Acquisition, Reconstruction and Modelisation.

Faysal Ahmed Khaled
Gallardo Arnaud
Labbé Emeric
Schiapparelli Ugo

This project has been achieved using QT.

/* ---- Compilation and execution---- *\

To compile it, run QTcreator and compile.
We use QT 5.  

You can also compile it in shell, using qmake and make.
It will make an executable named "Project".
Run it with ./Project

/* ---- Opening File ----*\

There is a toolbar  on the top of the window; to open an object click on "Fichier", "Ouvrir" and
select the file wanted.
We can open two file formats : .pgm3d and .obj

/* ---- Saving file ---- *\

We also implemented file saving. To save a file : "Fichier", "Sauvegarder" and
select the folder you want to save your data in.

We can change the transparancy using the slider on the left.

We can go from Surfacic to Volumic representation in the menu "Affichage".
Since we used one of those, you need to go back to "Personnalisé" to use the slider again.

/* ---- Controls ---- *\ 

Rotation can be done with the left click.
Use the wheel button to control the zoom.
Translations, following cardinal directions, are bind with keys:
Z :: Up
S :: Down
Q :: Left
D :: Right

/* ---- Improvement ---- *\

We could have avoided duplicating code. And we could have implemented a better data structure like an octree, 
to better manage the different components of a pgm3D.


