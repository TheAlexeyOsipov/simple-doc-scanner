# simple-doc-scanner

1. Detect document edges in the image using Canny
2. Find the largest contour with 4 points that correspond to the document
3. Apply a perspective transform to obtain the top-down view
4. Apply thresholding to obtain binary image
