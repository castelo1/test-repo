# test-repo
repositório de teste do GitHub Desktop

## Speech to Text App

A multi-language speech-to-text application that supports Portuguese, English, and Spanish.

### Features

- **Automatic Language Detection**: No need to select language - the app automatically detects if you're speaking Portuguese, English, or Spanish
  - Supported languages: English (US, UK), Portuguese (Brazil, Portugal), Spanish (Spain, Mexico, Argentina)
  - Smart language switching when recognition fails
  - Shows detected language in real-time

- **Real-Time Transcription**: See your speech converted to text in real-time with confidence indicators
- **Continuous Recording**: Keeps recording until you stop it
- **User-Friendly Interface**: Modern, responsive design that works on all devices
- **Copy to Clipboard**: Easily copy transcribed text
- **Clear Function**: Reset and start fresh anytime

### How to Use

1. Open `speech-to-text.html` in your web browser
2. Click "Start Recording" and allow microphone access
3. Speak clearly in Portuguese, English, or Spanish
4. Watch the app automatically detect your language
5. See your speech transcribed in real-time
6. Click "Stop Recording" when finished
7. Use "Copy Text" to copy the transcription to clipboard
8. Use "Clear" to reset and start over

### Browser Compatibility

This app uses the Web Speech API and works best with:
- Google Chrome (recommended)
- Microsoft Edge
- Safari

**Note**: Firefox has limited support for the Web Speech API.

### Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- Uses the Web Speech API (SpeechRecognition)
- No external dependencies required
- Fully client-side - no data is sent to external servers
