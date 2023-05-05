# Lane Detection System using Canny Edge Detection

This repository contains a lane detection system that uses Canny edge detection algorithm to detect the lanes in an image or video stream. The system is implemented in Python using OpenCV library.

## Installation

Before running the program, make sure you have the following dependencies installed:

- Python 3.x
- OpenCV library

You can install OpenCV library by running the following command:

```
pip install opencv-python
```

## Usage

To use the lane detection system, run the following command:

```
python detect_lanes.py <input_file>
```

Where `<input_file>` is the path to the input image or video file.

The output of the program will be displayed in a new window. The detected lanes will be highlighted in green.

## Example

Here's an example of how to use the lane detection system to detect lanes in an image:

```
python detect_lanes.py test_images/solidWhiteCurve.jpg
```

This will display the following output:

![Solid White Curve Lanes Detected](https://user-images.githubusercontent.com/1234567/1234567890/solidWhiteCurve_lanes_detected.jpg)

## Contributing

Contributions to this repository are welcome. To contribute, please create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
