# MyTranslator
This Python script allows you to perform voice-based translations with language detection. It utilizes the speech_recognition, deep_translator, and gtts libraries to achieve this functionality.

# Usage

### Installation
Make sure you have the required libraries installed. You can install them using pip:
pip install langdetect speech_recognition deep_translator gtts

### Language Detection
The script uses the langdetect library to detect the language of the input text. You can provide input in any language supported by langdetect.

### Translation
To perform translations, the script uses the Google Translate API through the deep_translator library.

### Text to Speech
The script can also convert text to speech using the gtts library.

### Voice Input
You can use the get_user_input() function to get user input through the microphone. This function will return the recognized text.

# Running the Translation Program
Run the get_translation() function to start the translation process.

Follow the prompts to choose between voice input and manual typing. Provide the text you want to translate and the target language.

The translated text will be spoken out loud and saved as an MP3 file.

You can choose to continue translating more text or exit the program.


