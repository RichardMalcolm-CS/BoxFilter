Based off of the boxFilter lab

boxFilterNPP.cpp has been updated to handle a large amount of greyscale images in the pgm file format. To accomplish this the code utilizes dirent to look through a directroy, in this case the imagebox folder in the project, then iterates through the files until all files names have been read. It proceeds to parse the file names from the output of readdir then preform the box filter and output the filtered image.
