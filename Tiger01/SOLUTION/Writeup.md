# Writeup
You can find the flags in any order. 

The supposed JPG file is actually a PNG file, as clued by the IEND chunk at the end of the file. 
Replacing the headers to match that of a PNG in any hexeditor will repair the file. 
Opening the PNG file will display a flag.

The second flag is hidden as base64. You can find this string either through the `strings` command, viewing the file bytes, or opening the image in a metadata tool after fixing it.
Decode the base64 string to find a flag. 
