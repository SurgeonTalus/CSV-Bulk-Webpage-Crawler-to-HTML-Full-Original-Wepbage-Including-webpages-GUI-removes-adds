# URL to HTML Converter

This Python script provides a simple GUI (Graphical User Interface) for converting a list of URLs from a CSV file to HTML files. The conversion is done by utilizing the `singlefile` Docker container to capture the full webpage content.

## Prerequisites

Make sure you have the following prerequisites installed before running the script:

- **Python:** Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

- **Docker:** The script relies on the `singlefile` Docker container to capture webpage content. Install Docker from [Docker's official website](https://www.docker.com/get-started).

- **Required Python Libraries:**
  - `tkinter`: Included in Python's standard library for GUI.
  - `requests`: Install it using `pip install requests`.
  - `beautifulsoup4`: Install it using `pip install beautifulsoup4`.
  - `appscript`: Install it using `pip install appscript`.
  - `mactypes`: Install it using `pip install mactypes`.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/url-to-html-converter.git
Navigate to the project directory:
bash
Copy code
cd url-to-html-converter
Install the required Python libraries:
bash
Copy code
pip install -r requirements.txt
Usage

Run the script by executing the following command:
bash
Copy code
python url_to_html_converter.py
The GUI window titled "URL to HTML Converter" will appear.
Click the "Browse CSV File" button to select a CSV file containing a list of URLs.
Choose a destination directory for saving the HTML files.
The script will process each URL, convert it to an HTML file, and save it in the specified directory.
Once the process is complete, the status label will indicate the success or cancellation of the operation.
Notes

The script uses the singlefile Docker container to capture webpage content, so make sure Docker is running before using the converter.
Ensure that the CSV file contains URLs in the first column.
The generated HTML files will be saved in the specified directory with filenames derived from the URLs.
Webpage URLs are added to the HTML files' comments for reference.
Feel free to customize the script or provide feedback for improvements.

Copy code


Usage

Run the script by executing the following command:
bash
Copy code
python url_to_html_converter.py
- The GUI window titled "URL to HTML Converter" will appear.
- Click the "Browse CSV File" button to select a CSV file containing a list of URLs.
- Choose a destination directory for saving the HTML files.
- The script will process each URL, convert it to an HTML file, and save it in the specified directory.
- Once the process is complete, the status label will indicate the success or cancellation of the operation.
Notes

- The script uses the singlefile Docker container to capture webpage content, so make sure Docker is running before using the converter.
- Ensure that the CSV file contains URLs in the first column.
- The generated HTML files will be saved in the specified directory with filenames derived from the URLs.
- Webpage URLs are added to the HTML files' comments for reference.
- Feel free to customize the script or provide feedback for improvements.
