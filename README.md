# Filters
Filters is a simple implementation of some of instagram filters like grayscale, sepia using C and Bitmap to dealing with photo as an array of pixels.

## Installation
You need to have C installed on your machine, and GCC Compiler.
## Usage
First you need to compile the program, so head to the path that you saved the project in and type
```bash
gcc filter.c [-filter] [PathOfInputImage].bmp [out].bmp
```
then you will notice an output file with the name you specified [out].bmp has been created in the folder, it's the image after the filter applied to it.
</br>
Here's the type of filters provided: </br>
"b" => for the blur</br>
"g" => for the grayscale.</br>
"r" => for reflect (mirror).</br>
"s" => for sepia.</br>
