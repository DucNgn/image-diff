## Get the difference between 2 images with OpenCV and Scikit

Based on tutorial from [pyimagesearch](https://www.pyimagesearch.com/2017/06/19/image-difference-with-opencv-and-python)

Paper Publication of Structural Similarity Index (SSIM): https://ece.uwaterloo.ca/~z70wang/publications/ssim.pdf

## Install & Run:
+ `python3 -m venv .env` to create virtual environment.
+ `source .env/bin/activate` to activate the virtual environment.
+ `pip3 install -r requirements.txt` to install dependencies.
+ `python3 src/image_diff --first {path_to_first_image} --second {path_to_second_image}` to start the program.

## Demo:

Using the 2 images in `src/test_img` outputs the result as following:

![demo](./demo.png)
