# harris-corner-detection
penCV has the function cv.cornerHarris() for this purpose. Its arguments are:

img - Input image. It should be grayscale and float32 type.
blockSize - It is the size of neighbourhood considered for corner detection
ksize - Aperture parameter of the Sobel derivative used.
k - Harris detector free parameter in the equation.
