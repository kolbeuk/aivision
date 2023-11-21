# aivision
Photofinderparm: Image Processing and OpenAI Integration Demo
Overview
Photofinderparm is a Python script demonstrating image processing using the OpenCV library and integration with the OpenAI API. It's designed as a demonstration tool to showcase how images can be split, encoded, and analyzed using OpenAI's powerful AI models. This script is ideal for developers and enthusiasts interested in exploring the capabilities of computer vision and AI.

Features
Image splitting into smaller sections using OpenCV.
Base64 encoding of images for API transmission.
Interaction with OpenAI's API to process images and text.
Measurement of API request time for performance analysis.
Requirements
Python 3.x
OpenCV (opencv-python)
OpenAI Python Library
NumPy
Requests
Argparse
Installation

Obtaining OpenAI API Key
To use this script, you must have an OpenAI API key. Obtain the key from OpenAI's website. 
After obtaining the key, set it in your environment variables as OPENAI_API_KEY.

Usage
To run the script, navigate to the directory containing Photofinderparm.py and use the following command format in your terminal:
python3 Photofinderparm.py [image_file_path] '[custom_text_message]'

Replace [image_file_path] with the path to your image file and [custom_text_message] with your desired text message for the API request.

Example:
python3 Photofinderparm.py storephoto.jpeg 'find lemongrass in this photo'

Note
This script is intended as a demonstration and may require modifications for production use.
