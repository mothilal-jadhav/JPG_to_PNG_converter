# JPG_to_PNG_converter

the idea is to make a converter that takes 2 arguments

- the source directory
- and the destination directory

first it has to go through all the files in the source directory and convert each .jpeg file into .png file. and add those png files into a new folder.

if the folder exists then add into that folder but if it does not exist, then create a new folder.

so to make these 2 possible, i will be importing **sys** and **os**

-> sys helps in taking the arguments , which are in our cases will be source and destination folders
-> os helps in finding the path exists or not, if does not exist then creates a new directory.