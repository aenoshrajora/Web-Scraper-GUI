# Web Scraper GUI

Web Scraper GUI is a Python program that allows users to scrape information from a specified URL and save the extracted content to a Word document (DOCX). The program uses a simple graphical user interface (GUI) built with the tkinter library for user interaction.

## Features

- Input a URL through the GUI.
- Fetch HTML content from the provided URL.
- Extract information (title and paragraphs) from the HTML content.
- Save the extracted information to a Word document (DOCX).

## Requirements

- Python 3.x
- Requests library: `pip install requests`
- BeautifulSoup library: `pip install beautifulsoup4`
- python-docx library: `pip install python-docx`
- tkinter library (usually included with Python)

## How to Use

1. Clone or download the repository to your local machine.

2. Install the required libraries:

    ```bash
    pip install requests beautifulsoup4 python-docx
    ```

3. Run the program:

    ```bash
    python web_scraper_gui.py
    ```

4. Enter the URL in the provided entry field and click the "Scrape" button.

5. The extracted information will be saved to a file named `Output.docx` in the same directory.

## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request. Contributions are welcome!

