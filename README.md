# odea-carib-otoliths
Data repository of fossilised and modern Caribbean otoliths from the O'dea lab. Data collected with Automorph from HullLab. 
To download Automorph and general user guides, visit https://github.com/HullLab/AutoMorph/tree/master

# <b> O'dea Lab Automorph User Guide </b>

by Abby Kelley and Katie Griswold

<b>Introduction</b>

AutoMorph extracts size data for multiple objects arranged on a dark background, photographed in a single series of vertically stacked images.  It prepares the images by aligning and rescaling the objects, segments the images into separate objects, focuses each object’s image stack into a single, often beautiful image, and then measures 2D and 3D traits for each object. These steps are carried out using a combination of Python, ZereneStacker, and Matlab programs. White there is currently no user interface, the process is simplified so that it can be executed rather simply in command line. Each step has a command (“prepare, “segment,” “focus –i,” “run2dmorph” and “run3dmorph”) that runs the requisite program in AutoMorph. Often, these commands also require a settings file that gives the AutoMorph program additional information about the images and objects being measured. I have also made a couple of my own command line scripts that speed up some of AutoMorph’s steps. This guide explains how to use AutoMorph on this computer. Good luck! -- Abby

PS-- Check out the AutoMorph website http://people.earth.yale.edu/automorph/pincelli-hull 

Updates 2018:
Automorph Version 2 now now exists! Check out the paper: http://onlinelibrary.wiley.com/doi/10.1111/2041-210X.12915/full --Katie
