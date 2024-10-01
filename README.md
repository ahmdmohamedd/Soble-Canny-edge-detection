# Edge Detection Using Sobel and Canny Filters

## Overview
This project demonstrates edge detection in images using two popular methods: Sobel and Canny filters. The implementation is done in Python using the OpenCV and Matplotlib libraries. The program reads an image named `image.png`, applies both edge detection techniques, and displays the results.

## Technologies Used
- **Python**: The programming language used for the implementation.
- **OpenCV**: A library for computer vision tasks that provides the functions for edge detection.
- **Matplotlib**: A library for plotting and visualizing images.

## Requirements
Before running the code, ensure you have the following libraries installed:

- OpenCV
- Matplotlib
- NumPy

You can install these libraries using pip:

```bash
pip install opencv-python matplotlib numpy
```

## Getting Started
1. **Clone the Repository**: Clone this repository to your local machine using the following command:
   ```bash
   git https://github.com/ahmdmohamedd/Soble-Canny-edge-detection
   ```

2. **Prepare the Image**: Ensure you have an image named `image.png` in the same directory as the notebook file.

3. **Run the Notebook**: Open the `sobel_canny_edge_detection.ipynb` file in Jupyter Notebook or any compatible environment.

4. **Execute the Code**: Run the cells in the notebook to see the original image, Sobel edge detection results, and Canny edge detection results.

## How It Works
- **Sobel Filter**: The Sobel filter calculates the gradient of the image intensity function. It operates in both the x and y directions, allowing it to detect edges in any orientation. The results from both directions are combined to produce the final edge map.
  
- **Canny Edge Detection**: The Canny method uses a multi-stage algorithm to detect a wide range of edges in images. It includes steps such as noise reduction, gradient calculation, non-maximum suppression, and edge tracing by hysteresis.

## Results
After running the notebook, you will see the following outputs:
- **Original Image**: Displays the input image.
- **Sobel Edge Detection**: Shows the edges detected using the Sobel filter.
- **Canny Edge Detection**: Displays the edges detected using the Canny filter.

## Contributing
Contributions are welcome! If you have suggestions for improvements or features, please open an issue or submit a pull request.

## Acknowledgments
- OpenCV for providing a powerful library for computer vision.
- Matplotlib for easy image visualization.
