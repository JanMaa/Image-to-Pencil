
# Image to Pencil Sketch

Using OpenCV Python library, transformed RGB image so that it resembles a pencil sketch.


## Steps reproduced

1. Loaded the image file.
2. Converted RGB image to grayscale - this will turn the image into a classic black-and-white photo;
3. Inverted the grayscale image - this is sometimes referred to as a negative image and can be used to enhance details;
4. Mixed the grayscale image with the inverted blurry image - this was done by dividing the pixel values of the grayscale image by the pixel values of the inverted blurry image; the result resembles a pencil sketch;