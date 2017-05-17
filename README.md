# Canny-Edge-Detector
1. Reads the cameraman Image and displays it as grayscale image.
2. Gaussian smoothing operator is applied  to the image and displays smoothed image.
3. The sigma and size of smoothing kernel are interactively selected by a FloatSlider and IntSlider. The default value for sigma is 5 and default value for size of filter is 7
4. Sobel Operator to smoothed image and displays magnitude and direction of edges as two seperate images
5. Non maximum supression algorithm applied to image and result shown as grayscale image
6. Double threshold algorithm which can be changed interactively by two float sliders are used and image shown as binary.
   8 connected neighborhood is used for double threshold algorithm.

Note:
No built in edge detector are used.
No Non maximum supression built in function is used.
