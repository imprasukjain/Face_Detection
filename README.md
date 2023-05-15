# Face Detector using Haar Cascade Model

This repository contains a face detection application that utilizes a pre-trained Haar cascade model. The application is capable of detecting faces in images and provides the count of faces present in the image. The pre-trained Haar cascade model is stored in the `data` folder.

## Requirements

To run this application, you need to have the following dependencies installed:

- Python 3.6+
- OpenCV
- NumPy

You can install the required dependencies by running the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone this repository to your local machine or download the ZIP file.

```bash
git clone https://github.com/imprasukjain/Face_Detection.git
```

2. Navigate to the project directory.

```bash
cd face-detector
```

3. Ensure that the image you want to detect faces in is located in the project directory or provide the full path to the image.

4. Run the application by executing the following command:

```bash
python Face_Detection.py --image <image_path>
```

Replace `<image_path>` with the path to your image. If the image is located in the project directory, you can simply provide the image filename.

5. The application will display the original image with bounding boxes around the detected faces. Additionally, it will output the total number of faces detected in the image.

## Example

Let's say you have an image called `family_photo.jpg` that you want to analyze for faces. Assuming the image is located in the project directory, you can run the application with the following command:

```bash
python face_detector.py --image family_photo.jpg
```

The application will display the image with bounding boxes around the detected faces and output the number of faces found.

## Notes

- The pre-trained Haar cascade model used in this application is stored in the `data` folder. You can replace this model with your own if desired. Just make sure to update the code accordingly.
- If you want to process multiple images, you can modify the code to accept a folder path as input and loop through all the images in that folder.
- This application is for educational purposes and provides a basic example of face detection using a Haar cascade model. For more accurate and advanced face detection, consider using deep learning-based approaches such as the ones provided by OpenCV's DNN module or other frameworks like TensorFlow or PyTorch.

