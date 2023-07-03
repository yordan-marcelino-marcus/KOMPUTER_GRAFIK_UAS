# README

This is a [Flask](http://flask.pocoo.org/) app for my final exam exercise.

Demo: [https://fumui-img-cropper.onrender.com](https://fumui-img-cropper.onrender.com)

Py Image Cropper is a web application that allows you to upload an image, preview it, crop it based on position and size, and download the resulting cropped image. The web app is built using Flask and OpenCV.

## Features

- Select an image file from your local device.
- Preview the selected image before cropping.
- Choose the crop position from predefined options.
- Specify the crop size as a numeric value.
- Crop the image based on the selected position and size.
- View the resulting cropped image.
- Download the cropped image.
- Download the cropping process as a markdown file.
## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/fumui/py-img-cropper.git
   ```

2. Change to the project directory:

   ```bash
   cd py-img-cropper
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Start the web app:

   ```bash
   python app.py
   ```

2. Open your web browser and go to `http://localhost:5000`.

3. Select an image file by clicking on the "Select image" button.

4. Preview the selected image.

5. Choose the crop position from the dropdown list.

6. Specify the crop size in pixels.

7. Click the "Crop" button to perform the crop operation.

8. View the resulting cropped image.

9. Download the resulting cropped image as a markdown file or an image.
