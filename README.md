# Sign Language Translator

## Overview
The Sign Language Translator is an innovative application designed to facilitate communication between Arabic speakers and the hearing-impaired community. By utilizing speech recognition technology, this application converts spoken Arabic phrases into animated sign language representations in real-time.

## Features
- **Speech Recognition**: The application listens for spoken Arabic phrases and converts them into text using Google's speech recognition API.
- **Animated Sign Language Representation**: Each recognized phrase is mapped to a corresponding GIF that visually represents the sign language gesture.
- **User-Friendly GUI**: Built with `tkinter`, the application features an intuitive interface that allows users to start and stop listening with the click of a button.
- **Multilingual Support**: The application supports both English and Arabic phrases, making it accessible to a broader audience.

## Technologies Used
- Python
- `tkinter` for GUI
- `speech_recognition` for audio processing
- `sounddevice` for audio input
- `PIL` (Pillow) for image handling
- `ipywidgets` for file upload interface (optional)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sign-language-translator.git
   cd sign-language-translator
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have the necessary audio input devices and permissions set up on your machine.

## Usage
1. Run the application:
   ```bash
   python app.py
   ```

2. Click on the "Start Listening" button to begin the speech recognition process. Speak clearly in Arabic, and the application will display the corresponding sign language GIFs for recognized phrases.

3. To stop the application, simply click the "Stop" button.

## Adding GIFs
To add new sign language GIFs:
1. Place your GIF files in the `data` folder.
2. Ensure that the filenames match the phrases in the `word_to_sign` dictionary within the code.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Thanks to the developers of the libraries used in this project.
- Special thanks to the community for their support and feedback.

---

Feel free to reach out if you have any questions or need assistance!
