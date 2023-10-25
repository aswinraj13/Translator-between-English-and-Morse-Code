# Morse Code Converter

This Python code provides a simple Morse code converter application with a graphical user interface (GUI). It allows users to convert text to Morse code and vice versa. Here is a brief overview of the code and how to use it:

## Features

- Converts English text to Morse code and vice versa.
- Provides a user-friendly GUI for easy interaction.
- Supports both text input and output.
- Utilizes two classes for conversion: `abctomorse` and `morsetoabc`.
- Allows users to choose between English to Morse and Morse to English conversion.

## Usage

1. Run the code, and a graphical user interface (GUI) window will appear.
2. You'll find the following components in the GUI:
   - **Input:** A text area where you can enter the text you want to convert.
   - **Output:** A text area where the converted result will be displayed.
   - **Radio Buttons:** Choose between "Morse to English" and "English to Morse" conversion.
   - **Convert Button:** Click this button to perform the conversion based on your selection.

## Code Structure

The code consists of the following main classes:

- `abctomorse`: Handles English to Morse code conversion.
- `morsetoabc`: Handles Morse code to English conversion.
- `GUI`: The main graphical user interface class for user interaction.

The code utilizes the `tkinter` library for building the GUI.

## Example

1. Enter a text string in the "Input" text area.
2. Choose either "Morse to English" or "English to Morse" using the radio buttons.
3. Click the "Convert" button.
4. The converted result will be displayed in the "Output" text area.

**Note**: The Morse code conversion for English letters and digits is based on predefined Morse code representations stored in the `arr` list.

## Dependencies

- This code uses the `tkinter` library for GUI development. Ensure you have it installed.

## Additional Information

- You can expand the Morse code conversion dictionary in the `arr` list to include more characters or symbols.
- Feel free to customize the GUI's appearance to suit your preferences.

Enjoy using the Morse Code Converter!
