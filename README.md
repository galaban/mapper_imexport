# Galaban's Mapper Import/Export plugin
The purpose of this plugin is to expand the mapper commands to Import and Export custom exits from the mapper database.

The format of this plugin is:

mapper export <filename>
mapper import <filename>

This outputs a .csv file into the same directory as the mapper database.  To import a file, you must place the file in the same directory as the mapper database and specify the file name only.  For example:

mapper export outdata

This will create a new file called "outdata.csv".

mapper import outdata.csv

This imports the "outdata.csv" file

