# Speech to Text v1.1.0
## Overview
This project allows users to convert speech into text and save the result in a `.txt` file. The project uses the `speech_recognition` library and Google's Speech Recognition API to convert the speech to text and saves it in a file for further use.

## Features
- Supports speech recognition in Thai, English, Chinese, and Japanese.
- Converts speech to text and displays it on the console.
- Saves transcribed text to a `.txt` file based on the selected language.
- After each transcription, users can continue ('y') or exit ('n').
  
## Example
- The user selects a language (Thai, English, Chinese, or Japanese).
- The user speaks, and the app converts and displays the text.
- The text is saved to `output_thai.txt`, `output_english.txt`, `output_chinese.txt`, or `output_japanese.txt`.
- Example: Speaking "ได้ยินฉันไหมฉันเป็นคนไทย" saves to output_thai.txt.

### Installation
1. Clone or download the repository.
   ```bash
   git clone https://github.com/pathanin-kht/SpeechToText.git

3. Install the required dependencies:
   
   ```bash
   pip install -r requirements.txt
4. Run the code:
   
    ```bash
    python speech_to_text_py

## License
This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

## Contact
For feedback or inquiries, feel free to reach out via [pathanin.kht@gmail.com](pathanin.kht@gmail.com).

