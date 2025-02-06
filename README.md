# Emotion-Aware Music Composer 🎵🎭

## Overview
The **Emotion-Aware Music Composer** is an AI-powered system that generates music in real time based on the user's emotional state. By analyzing voice tone, facial expressions, or text input, the AI detects emotions and produces personalized melodies that match the user's mood.

## Features
- 🎤 **Voice Emotion Detection**: Analyzes speech tone and pitch.
- 📷 **Facial Expression Analysis**: Identifies emotions from facial expressions.
- 📝 **Text Sentiment Analysis**: Understands emotions from written input.
- 🎼 **AI-Generated Music**: Uses deep learning to create emotionally aligned melodies.
- 🎧 **Real-Time Personalization**: Adapts music dynamically as emotions change.

## Technologies Used
### **Emotion Detection**
- **Voice Analysis**: `Librosa`, `OpenSMILE`, `TensorFlow`
- **Facial Expression Recognition**: `Mediapipe`, `OpenCV`, `CNN`
- **Text Sentiment Analysis**: `Hugging Face Transformers`, `BERT`

### **Music Generation**
- **Deep Learning Models**: `Magenta`, `MuseNet`, `LSTM`
- **Music Data Handling**: `MIDI`, `Lakh Dataset`, `MAESTRO Dataset`
- **Audio Processing**: `pydub`, `FluidSynth`

## Installation
### **Prerequisites**
- Python 3.9+
- Virtual environment (recommended)

### **Setup Instructions**
```bash
# Clone the repository
git clone https://github.com/yourusername/emotion-aware-music-composer.git
cd emotion-aware-music-composer

# Create a virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Usage
### **1. Running the Emotion Detection Module**
```bash
python emotion_detection.py --mode voice  # For voice-based emotion detection
python emotion_detection.py --mode face   # For facial expression analysis
python emotion_detection.py --mode text   # For text sentiment analysis
```

### **2. Generating Music Based on Emotion**
```bash
python music_generator.py --emotion happy  # Generates music for a happy mood
```

### **3. Full Pipeline Execution**
```bash
python main.py  # Detects emotion and generates music in real time
```

## Project Structure
```
📂 emotion-aware-music-composer
├── 📁 datasets             # Training datasets (RAVDESS, FER2013, MAESTRO)
├── 📁 models               # Pre-trained and custom-trained models
├── 📁 src
│   ├── emotion_detection.py  # Emotion detection logic
│   ├── music_generator.py    # Music composition based on detected emotion
│   ├── main.py               # End-to-end pipeline
├── 📄 requirements.txt      # Required Python libraries
├── 📄 README.md             # Documentation
```

## Datasets Used
- **RAVDESS**: Speech Emotion Recognition Dataset
- **FER2013**: Facial Emotion Recognition Dataset
- **MAESTRO**: Piano Performance Dataset for Music Generation

## Future Enhancements 🚀
- **💡 Real-time feedback loop**: Improve model adaptation to user emotions.
- **📱 Mobile app integration**: Deploy as a mobile application.
- **🎭 Multi-modal emotion fusion**: Combine voice, face, and text inputs for more precise results.
- **🌍 Multi-language support**: Extend text analysis to multiple languages.

## Contribution Guidelines
Contributions are welcome! To contribute:
1. **Fork the repository**.
2. **Create a new branch** (`feature/your-feature-name`).
3. **Commit your changes** and push to your fork.
4. **Submit a pull request**.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
- **Author**: Goal Gamal
- **GitHub**: [goalgamal](https://github.com/goalgamal)
- **Email**: goalgamal8@gmail.com

---

🎶 **Let AI Compose Music That Resonates With Your Emotions!** 🎵

