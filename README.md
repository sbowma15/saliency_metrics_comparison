Saliency Metrics Comparison

This Python script, saliency_metrics_comparison.py, is designed for comparing saliency metrics (MSE, PSNR, SSIM) on a given image using the OpenCV library for image processing.

Prerequisites

Ensure you have the required libraries installed before running the script:

bash
Copy code
pip install opencv-python matplotlib
Usage
Open the script in your Python environment.

Adjust the file path in the cv.imread function to the location of your input image:

python
Copy code
imA = cv.imread("/path/to/your/Saliency0.jpg")
Run the script.

Output
The script provides the following outputs:

Displays the original image.

Displays the saliency map generated using the Spectral Residual method.
Calculates and displays the values of MSE, PSNR, and SSIM for the original image.
Feel free to experiment with different images and explore how saliency metrics change based on the saliency map generated.

Notes

The script uses the Spectral Residual method for generating saliency maps, and the calculated metrics are based on the comparison of the original image and itself. You can modify the script to compare different images as needed.
