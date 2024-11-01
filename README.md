# ImageProcessing
This project was aimed at becoming familiar with the basics of image processing. This project has 6 different sections.
Section A: 
In this section an image was displayed at first, and then since it was an RGB image 3 channels of it were splitted and displayed as blue, green and red channels.
Next, the original image was converted into greyscale without using any built-in function, and with solely the formula for greyscale, which is provided in the notebook.
The same picture was converted into hsv with both built-in functions and formulas. At last, the red color from the image was extracted and displayed.
Section B: 
In this section the histogram ( frequency of pixels) were plotted and then with the use of cumulative distribution function, we match the histogram of one image to the other.
Section C:
In this section, I applied 3 different filters on an image, including 2 median filters and one gaussian and then compared their results. Though it may seem that applying 3x3 median filter twice would do the same thing as 9*9 median filter, it's not true. Applying 3x3 filter twice leads to losing more information than just using the 9x9 median once. twice of the 3x3 filter gives quite the same result as 5x5 gaussian filter although the 5x5 gaussian filter removes less details from image. Moreover, the PSNR of the results was computed and compared.
Section D:
In the next section, histogram equalization was applied on an image to enhance its contrast.
Section E: 
In this section, given an image with salt-and-paper noise, I used a median filter, which is the most suitable filter for removing this type of noise. In summary, this filter replaces each pixel value with the median of its neighbourhood.
Section F:
In the last section, the chosen image was initially blurred by a gaussian filter, and then unsharp mask was applied on it.
