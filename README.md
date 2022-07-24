
# Image To Pencil Sketch

- Reading the image in RBG format and then convert it to a grayscale image. This will turn an image into a classic black and white photo. Then the next thing to do is invert the grayscale image also called negative image, this will be our inverted grayscale image. Inversion can be used to enhance details. Then we can finally create the pencil sketch by mixing the grayscale image with the inverted blurry image. This can be done by dividing the grayscale image by the inverted blurry image. Since images are just arrays, we can easily do this programmatically using the divide function from the cv2 library in Python.

## In this

 - [Code in Jupyter Notebook](https://github.com/hellfire95/Image_to_pencil_sketch/blob/main/Image%20To%20pencil%20Sketch%20Project.ipynb)
 - [Image](https://github.com/hellfire95/Image_to_pencil_sketch/blob/main/lenna.png?raw=true)

## Features

- Convert  any image to a sketch

- Python LAnguage 
- Opencv library 

## Screenshots
- Image 

![Image](https://github.com/hellfire95/Image_to_pencil_sketch/blob/main/lenna.png?raw=true)

- Converted Image

![Image](https://github.com/hellfire95/Image_to_pencil_sketch/blob/main/pencil%20Image.png?raw=true)