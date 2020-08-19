# Create_a_Pencil_Sketch_Portrait_with_Python_OpenCV
Interesting image filter effects, such as a pencil sketch or a cartoonizer effect, do not have to be very computationally involved to look good. In fact, in order to create a beautiful black-and-white pencil sketch effect, all you essentially need is some blurring and two image blending techniques called dodging and burning.

Using OpenCV and Python, an RGB color image can be converted into a pencil sketch in four simple steps:

1. Convert the RGB color image to grayscale.
2. Invert the grayscale image to get a negative.
3. Apply a Gaussian blur to the negative from step 2.
4. Blend the grayscale image from step 1 with the blurred negative from step 3 using a color dodge.
