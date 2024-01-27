# Freezer Item Counting OpenCV in Google Colab

# Goal
Count the number of items in the given freezer images.

# User Story
As a user I should provide a path to the image, and the program should count and display the information
about the number of items in the image. 

## Usage

1. **Install Required Libraries:**
   - Make sure you have OpenCV and NumPy installed. You can install them using:
     ```bash
     pip install opencv-python numpy matplotlib
     ```

2. **Run the Script:**
   - Execute the provided Python script to perform item detection.

3. **Adjust Parameters (Optional):**
   - You may need to adjust parameters such as blur size, Canny edge detection thresholds, and dilation iterations based on the characteristics of your images.

4. **View Results:**
   - The script will print the number of detected contours (potential items) and display the original image with contours.

## Files

- `freezer_image (1).png` and `freezer_image (2).png`: Sample image for item detection.

## Example of item detection
![Screenshot (257)](https://github.com/anushkaspatil/freezer_items_count/assets/103093836/d4ed1854-543f-4b70-9ab2-eb48c353a9f5)


