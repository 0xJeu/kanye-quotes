# Kanye-quotes

<img width="518" alt="Screenshot 2023-06-19 at 1 58 23 PM" src="https://github.com/0xJeu/kanye-quotes/assets/129988927/c88ceae2-3ac8-4391-98ae-6e165b1cfe52">

This Python code creates a GUI application that displays quotes from Kanye West. It uses the Tkinter library for the graphical user interface and the requests library to make an API call and fetch the quotes.

## How It Works

- The code imports the necessary modules, Tkinter, and requests.

- The `get_quote()` function is called when clicking the "Kanye" button. It sends a GET request to the "https://api.kanye.rest/" API endpoint, retrieves the response data in JSON format, and extracts the quote. The quote is then displayed in the GUI by updating the `quote_text` item on the canvas.

- The GUI layout consists of a canvas to display the background image and the quoted text, as well as a button with Kanye West's image. When the button is clicked, it triggers the `get_quote()` function.

## How to Use

To use this code, follow these steps:

1. Make sure you have Python installed on your system.

2. Import the necessary modules (`tkinter` and `requests`).

3. Copy the provided code into a Python file (e.g., `kanye_says.py`).

4. Save the image files "background.png" and "kanye.png" in the same directory as the Python file. These images will be displayed in the GUI.

5. Open a terminal or command prompt and navigate to the directory where the Python file is saved.

6. Run the Python file using the command: `python kanye_says.py`.

7. The GUI window titled "Kanye Says..." will open.

8. Click the "Kanye" button to fetch and display a random quote from Kanye West.

9. The quote will be displayed on the canvas along with the background image.

## Acknowledgments

This code demonstrates the implementation of a simple Kanye West quote generator using Tkinter and requests. Feel free to modify and customize it according to your preferences and requirements.
