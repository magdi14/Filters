# Filters
Filters is a simple implementation of some of instagram filters like grayscale, sepia using C and Bitmap to dealing with photo as an array of pixels.

## Installation
You need to have C installed on your machine, and GCC Compiler.
## Usage
First you need to compile the program, so head to the path that you saved the project in and type
```bash
gcc filter.c
```
then try run the output file with 
```bash
./filter [-filter] [PathOfInputImage].bmp [out].bmp
```
Here's the type of filters provided: 
"b" => for the blur
"g" => for the grayscale.
"r" => for reflect (mirror).
"s" => for sepia.
