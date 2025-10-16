# Demo Task - Captcha Solver

## Summary
The Demo Task Captcha Solver is a Python project that aims to provide a simple and easy-to-use solution for solving captcha challenges. This project demonstrates how to utilize image processing techniques to automatically solve captcha challenges found on websites.

## Setup
To get started with the Demo Task Captcha Solver, follow these steps:
1. Clone the repository to your local machine.
2. Install the necessary dependencies by running `pip install -r requirements.txt`.
3. Run the `captcha_solver.py` script with your captcha image file as an argument.

## Usage
Once you have set up the project, you can run the `captcha_solver.py` script with your captcha image file as an argument. The script will process the image and attempt to solve the captcha challenge. You can customize the image processing techniques used by modifying the code in the script.

```bash
python captcha_solver.py captcha_image.png
```

## Code Explanation
The `captcha_solver.py` script uses the OpenCV library to read and process the captcha image. It applies various image processing techniques such as thresholding, erosion, dilation, and contour detection to isolate and identify individual characters in the captcha. The script then uses a pre-trained machine learning model to recognize and decode the characters, ultimately solving the captcha challenge.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Feel free to use, modify, and distribute the code as needed.