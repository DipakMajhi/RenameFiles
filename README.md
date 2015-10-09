# RenameFiles
It will help to rename a bunch of files along with it their formats can also be changed.

Renaming :

just change the folder paths along with their respective file formats.

example:
imFolder = 'G:\HMMtry\im2';
dirData = dir([imFolder, '\*.jpg']);

Format changing :

Change the output folder path and your desired file format their.

example:
newName = sprintf('testimg%02d.jpg',iFile);

It shall rename all files from the source folder and shall give the output in the output folder with the assigned file format.

Make sure you keep a back up. 
