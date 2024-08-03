
# Text-To-Speech Converter

This project is a simple Text-To-Speech (TTS) Converter that allows users to input text, choose a voice, and hear the text spoken aloud. The application provides controls to adjust the speech rate and pitch.

## Files

- `index.html`: The main HTML file that structures the TTS Converter interface.
- `styles.css`: The CSS file that styles the TTS Converter interface.
- `script.js`: The JavaScript file that handles the functionality of the TTS Converter using the Web Speech API.

## Features

- Select from a list of available voices.
- Adjust the speech rate using a slider.
- Adjust the pitch using a slider.
- Input text into a textarea to be spoken aloud.
- Buttons to start and stop the speech synthesis.

## Usage

1. Clone the repository.
2. Ensure all three files (`index.html`, `styles.css`, and `script.js`) are in the same directory.
3. Open `index.html` in a web browser (works best in Chrome).

## Compatibility

- This application works best in Chrome due to its comprehensive support for the Web Speech API.

## How It Works

1. **index.html**: Creates the structure of the interface, including dropdowns, sliders, a textarea, and buttons.
2. **styles.css**: Styles the interface to make it visually appealing and user-friendly.
3. **script.js**: Uses JavaScript to:
   - Populate the voice selection dropdown with available voices.
   - Handle the start and stop actions for the speech synthesis.
   - Adjust the speech rate and pitch based on user input.

## Future Improvements

- Add more styling and animations to enhance the user experience.
- Improve compatibility with other browsers.
- Implement additional features like saving and loading text.

## License

This project is open source and available under the MIT License.
