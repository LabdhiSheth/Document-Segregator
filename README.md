# Document-Segregator

Python Application to separate the files according to their types and copying those files from original folder to destination folder.
CSV files records -
1. File name 
2. Timestamp of creation
3. Timestamp of last modification
4. Original file path
5. Path after moving it to two corresponding type folder
6. Extension

This application is done using shutil, os, random , pandas and time libraries of python.

Flow of the program
1. Empty D1 and D1_copy folders are made.
2. 12 folders of different file types each with 30 files are added in D1 folder
3. All the files and folders are shifted from D1 to D1_copy folder
4. Time stamp of creation, time stamp of modification, original file path, modified file path and other attributes are added to the CSV file.
