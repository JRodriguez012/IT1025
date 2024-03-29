## Javi Rodriguez / September 26, 2021

## Executive Summary 
In Lab 4, we learn a few of the basics of the Python programming language and how to use Python IDLE. Python IDLE consists of the interactive shell where single instructions can be run and the file editor where entire Python programs can be written, saved, and loaded for later use. We also learn about raster and vector graphics and the differences between the two. Lab 4 explores some of the different file formats that are used to save images. Lastly, I used Vectr to create a logo that will be used in a later lab.

## Python IDLE
The interactive shell is good for running Python instructions one at a time as the shell runs the instruction that you typed as soon as you press ENTER. The file editor is for writing entire Python programs. With the file editor, you can type in multiple instructions, save the file, and run the entire program. The file editor can open these saved files to be reloaded and edited later. You can tell the difference between the file editor and the shell because the shell has the >>> prompt while the file editor does not.

## Code Examples
### Variable:
Ex. myName

A variable is a space in the computer's memory where you can store a single value. Variables can be used to retrieve values in different parts of your program. The author uses the variable names spam, bacon, and eggs as generic names used for examples. These generic names were inspired by Monty Python "Spam" sketch.
### Assignment statement:
Ex. myName = 'Javi'

Assignment statements are used to store values in variables. An assignment statement consists of a variable, an equal sign, and the value that will be stored. In the example, the value 'Javi' is stored in the variable myName.
### Function:
Ex. print(myName)

A function is a piece of code that does a specific task. Functions sometimes take arguments, values that are passed to the function that the function can then use to do its task. The print function takes a string value as an argument and displays that string on the screen as text.
### Three data types:
Ex. integer (5), floating-point number (5.0), string ('5', 'Javi')

A data type is a category of values. Every value belongs to exactly one data type. The integer (int) data type describes a whole number. Floating-point numbers (floats) are numbers with a decimal point. A string is a group of characters surrounded by single quote (') characters that note where the string begins and ends. The string value is the text value where the single quote characters are ignored.
## Graphics

### Raster vs. Vector Graphics
A raster image is made up of thousands of tiny pixels. Small raster images lose quality when they are enlarged because these individual pixels become more visible. Vector graphics are rendered using a special form of geometry. Vector graphics are able to be enlarged without losing quality. Raster images are used more for photography, while vector graphics are used more in the professional design world for logos, fonts, etc.
### Lossless vs. Lossy Compression
The decision to use lossless or lossy compression depends on what the developer's needs are for the image. If a high quality image is necessary, a lossless image format should be used as all the data from the original image is preserved. If keeping file sizes small is important, a lossy image format should be used as some of the original image data is removed and the file size is reduced.
### File Formats
GIF is a good file format for simple graphics as it supports up to 8 bits per pixel, therefore an image can have up to 256 distinct RGB colors. Unlike the other two formats, GIFs allow for animated images. JPEG is an appropriate format for photos without high contrast. JPEGs allow the designer to adjust the amount of compression used. Both GIFs and JPEGs are both suitable for keeping file sizes small. PNG is a good format for illustrations and photos with high contrast. PNGs support transparency including alpha channel transparency. Both GIFs and PNGs use lossless compression, while JPEGs use lossy compression for files.
### File Properties
In the file's properties, you can find the name and location of the file along with the file format and the size of the file. You can also find see when the file was created and the last time it was modified or accessed. My logo file was saved as an SVG Document and takes up 865 KB.

## Conclusion
During this lab, I used the Python IDLE for the first time. I have used some other IDEs before like visual studio and Eclipse, but I enjoyed the simplicity of IDLE and the ability to use the interactive shell for learning the basics of the language. I learned the difference between raster and vector graphics. After this lab, I have a better understanding of differences between the GIF, JPEG, and PNG file formats, how each of these formats compress files, and the appropriate uses for each format. My favorite part of this lab was creating a logo using Vectr. I have some experience using Inkscape for vector graphics, so I was easily able to use Vectr  after completing the tutorial. I am a huge fan of board games, so I decided to create a logo for a made up board game blog/review site.
