## BoxFilter on many images

This project is based off of the boxfilter lab. boxFilterNPP.cpp has been updated to handle a large amount of greyscale images in the pgm file format. To accomplish this the code utilizes dirent to look through a directroy, in this case the imagebox folder in the project, then iterates through the files until all files names have been read. It proceeds to parse the file names from the output of readdir then preforms a box filter and output the filtered image.

## Project structure

The common folder contains header files used by the project.

The boxFilterNPP folder contains the source files for the project

## Running the project

You can either utilize the visual studio code ide within coursera or your own ide, however using your own ide may require setup, if using visual  studio code in coursera, click build, then click run to build and run the project.

The once run, the project should execute a filtered version of all the images within the image box folder, feel free to add pgm images to the image box folder and see the result.

## Dependencies and Prerequisites

This project depends on NPP and FreeImage.

Additionally, Nvidia's Cuda toolkit will need to be installed and configured in order for this project to run if you are not using coursera to build and run the code

