# JPG_to_PNG_converter

the idea is to make a converter that takes 2 arguments

- the source directory
- and the destination directory

first it has to go through all the files in the source directory and convert each .jpeg file into .png file. and add those png files into a new folder.

if the folder exists then add into that folder but if it does not exist, then create a new folder.

so to make these 2 possible, i will be importing **sys** and **os**

-> sys helps in taking the arguments , which are in our cases will be source and destination folders
-> os helps in finding the path exists or not, if does not exist then creates a new directory.

- third step is to loop through the source folder and convert the jpg into png formats and then save them to new folder.


Project is successful and all the files are converted into png files