# Grayscale
Algorithm 
    Get the red green blue values of each pixel.
    
    
    
    Subtract each color value from 255 and save them as new color values.
    
    
    
    Create a new pixel value from the modified colors.
    
    
    set the new value to the pixel.
    
    
    For colored images, we will subtract 255 from all the values of all 3 channels (RGB) and take its absolute value (positive value).
    
    
    For a grayscale image, we have just 1 channel and there also we will subtract 255 from those pixel values (pixel value ranges from 0-255 in grayscale images) and take absolute values.
    
    
    We can consider negative images as the exact opposite of the original images, if we add both, the original image and the negative image, we will get a pure white image.
