# Digital_Image_Fundamentals_Cat_Image

This utilizes various image processing techniques using libraries such as PIL, Matplotlib, NumPy, and scikit-image. Let's break down the functionalities provided by each section:

1. **Image Display and Histogram**:
   - The code loads an image (`Cat.jpeg`), displays it using Matplotlib, and then plots the color histogram of the image.

2. **Edge Detection**:
   - The code performs edge detection on the loaded image using the Sobel filter from scikit-image.

3. **Image Rotation**:
   - The code rotates the image by 180 and 90 degrees and displays the results.

4. **Image Metadata**:
   - Extracts metadata from the image using the `_getexif()` method.

5. **3D Surface Plot**:
   - Converts the grayscale image to a 3D surface plot.

6. **Visual Intensity Array**:
   - Displays the image as a visual intensity array.

7. **Normalization**:
   - Normalizes the pixel values of the grayscale image to be between 0 and 1.

8. **Image Saturation and Noise**:
   - Creates an image with saturation and noise.

9. **Storage Calculation**:
   - Calculates the storage required for images with different dimensions and bit depths.

10. **Conversion of Coordinates**:
    - Converts 2D coordinates to a linear index for column-major order.

11. **Image Resizing**:
    - Resizes the image to half its original dimensions.

12. **Reducing Intensity Resolution**:
    - Reduces the intensity resolution of the image.

13. **Reducing Intensity Levels**:
    - Reduces the number of intensity levels in the image.

14. **Isopreference Curves**:
    - Plots isopreference curves for different image types based on spatial and intensity resolutions.

Each section of the code demonstrates a specific aspect of image processing, including visualization, manipulation, and analysis.
