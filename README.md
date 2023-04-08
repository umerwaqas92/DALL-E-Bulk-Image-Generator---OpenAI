# DALL-E-Bulk-Image-Generator---OpenAI


![DALL-E Image Generator Screenshot](https://github.com/umerwaqas92/DALL-E-Bulk-Image-Generator---OpenAI/raw/main/Screenshot%202023-04-08%20at%205.09.04%20PM.png)


"# DALL-E Image Generator

The DALL-E Image Generator is an application that uses OpenAI's DALL-E model to generate high-quality images based on input data from a CSV file. The application includes a user interface that allows users to enter their OpenAI API key, select the desired image size, and choose a CSV file with input data for the images. Once the parameters have been set, users can generate the images with a single click of a button. The application will display a loading indicator while the images are being generated, and will save the images in a `generated_img` folder within the current directory.

## Installation

To install the DALL-E Image Generator, you will need to have Python 3.7 or higher installed on your system. You will also need to install the required packages listed in the `requirements.txt` file by running the following command:



## Usage

To use the DALL-E Image Generator, follow these steps:

1. Open a terminal or command prompt and navigate to the directory where the application files are located.
2. Run the `gui.py` file by typing `python gui.py` in the terminal or command prompt.
3. Enter your OpenAI API key in the "OpenAI API Key" field.
4. Select the desired image size from the drop-down menu.
5. Click the "Select Input CSV File" button and choose the CSV file with the input data.
6. The "Count" label will display the number of rows in the selected CSV file.
7. The "Selected file" label will display the name of the selected CSV file.
8. The "Estimated cost" label will display the estimated cost of generating the images based on the number of rows in the CSV file and the selected image size.
9. Click the "Generate Images" button to generate the images. The button will be disabled while the images are being generated.
10. A loading indicator will be displayed while the images are being generated.
11. Once the images have been generated, a message box will be displayed to confirm that the images have been saved in the `generated_img` folder.
12. You can exit the application by closing the window or pressing Ctrl+C in the terminal or command prompt.

## Contributing

Contributions to the DALL-E Image Generator are welcome and encouraged! If you find a bug or have a feature request, please create an issue on the GitHub repository. If you would like to contribute code, please fork the repository and submit a pull request.

## License

The DALL-E Image Generator is licensed under the MIT License. See the `LICENSE` file for more information.

## Contact

If you have any questions or comments about the DALL-E Image Generator, please contact us at um.waqas.khan@gmail.com.
"""

# Write the README content to a file
with open("README.md", "w") as f:
    f.write(README_CONTENT)

# Print a message to confirm that the file has been written
print("README file has been generated.")


https://fluttydev.gumroad.com/l/DALL-EBulkImageGenerator
