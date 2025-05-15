# Multimodal Emotion Detection from Face and Voice

This project detects emotions from facial images and voice recordings using deep learning and audio processing techniques. It supports facial emotion recognition and voice emotion classification, along with speech transcription and language detection.

## Introduction

Emotion detection is important for enhancing human-computer interaction and understanding user sentiment. This project uses:

- A pre-trained CNN model for detecting facial emotions from images.  
- Audio feature extraction combined with an SVM classifier to recognize emotions in voice recordings.  
- OpenAI Whisper for automatic speech transcription and language identification.

Supported facial emotions include: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral. Voice emotions classified include: happy, sad, angry, and neutral.

## Project Structure

- Python script or notebook containing code for:  
  - Installing dependencies  
  - Downloading the pre-trained face emotion model  
  - Facial emotion detection  
  - Voice emotion feature extraction, classification, and transcription  
  - File upload handling for image and audio files  

## Technologies Used

- Python  
- Keras (CNN for facial emotion detection)  
- OpenCV (Face detection and image processing)  
- Librosa (Audio feature extraction)  
- Scikit-learn (SVM classifier)  
- Pydub (Audio format conversion)  
- OpenAI Whisper (Speech transcription and language detection)  
- Google Colab (Interactive environment for file uploads and visualization)  

## How to Run

1. Open the notebook or script in **Google Colab**.  
2. Run the setup cells to install dependencies and download pre-trained models.  
3. Upload an image (.jpg/.png) or audio file (.mp3/.wav/.mp4/.opus) when prompted.  
4. View the detected facial emotion or voice emotion along with speech transcription and detected language.

## Future Enhancements

- Train the voice emotion classifier on a real, labeled dataset for better accuracy.  
- Support multi-face detection and multi-speaker audio analysis.  
- Build a user-friendly web or mobile app interface for real-time emotion recognition.

## License

This project is developed for educational and research purposes.
