SnapEdit is a user-friendly image editing web application built with Streamlit. The app allows users to upload images and apply various edits, 
including filters, rotation, text addition, and basic image corrections such as contrast, brightness, and sharpness adjustments.

**# Features**

**Image Uploading:**
Upload images in jpg, png, or jpeg formats.
Display the original image in the sidebar for comparison.

**Filters:**

Grayscale: Converts the image to black and white.
Sepia: Applies a warm, reddish-brown tone to the image.
Blur: Blurs the image using Gaussian blur, with an adjustable blur amount.
Contour: Detects edges in the image using Canny edge detection.
Sketch: Converts the image to a sketch-like appearance.

**Image Rotation:**

Rotate the image to any angle between -180 and 180 degrees.

**Add Text to Image:**

Add custom text to the image.
Adjust the size and position of the text.

**Image Corrections:**

Contrast: Adjusts the contrast of the image.
Brightness: Adjusts the brightness of the image.
Sharpness: Adjusts the sharpness of the image.

**Tools:**

Image Cropping: Crop the image with a customizable aspect ratio.
Real-time Update: Toggle real-time updates while cropping.

**# How to Run the Application**

**Clone the Repository:**

git clone https://github.com/your-username/snapedit.git

**Install the Required Libraries:**

pip install -r requirements.txt

**Run the Application:**

streamlit run app.py

**Open in Browser:**

The application should open automatically in your default web browser.
If not, navigate to http://localhost:8501 in your browser.
