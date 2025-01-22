# Speech-to-Text and Save

## Overview
This project allows users to convert speech into text and save the result in a `.txt` file. The user can choose between Thai and English for the speech recognition process. The project uses the `speech_recognition` library and Google's Speech Recognition API to convert the speech to text and saves it in a file for further use.

## Features
- Users can select a language for speech recognition, either Thai or English.
- Users speak into the microphone to record their speech.
- The program processes the audio and converts it into text.
- The transcribed text is displayed on the console for immediate feedback.
- The transcribed text is saved to a `.txt` file named according to the selected language.
- After each transcription, users can choose to continue recording or exit the program.

## Example
- The user speaks into the microphone, and the application converts the speech to text and displays the result.
- The text is saved to a file named `output_thai.txt` or `output_english.txt` depending on the language selected.
- After each transcription, the user can choose to continue ('y') or stop ('n').
- For example, speaking "ได้ยินฉันไหมฉันเป็นคนไทย" will save:
  
  ```bash
  Text (Thai):
  ได้ยินฉันไหมฉันเป็นคนไทย
- If the user stops, the session ends and the text is saved in the file.

### Installation
1. Clone or download the repository.
2. Install the required dependencies:
   
   ```bash
   pip install -r requirements.txt
4. Run the code:
   
    ```bash
    python speech_to_text_py

## License
This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

## Contact
For feedback or inquiries, feel free to reach out via [pathanin.kht@gmail.com](pathanin.kht@gmail.com).

