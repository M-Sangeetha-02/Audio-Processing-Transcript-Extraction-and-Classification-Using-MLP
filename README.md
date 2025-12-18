# Audio Processing: Transcript Extraction and Classification Using MLP

##  Project Overview
This project demonstrates two key applications of audio processing in machine learning:
1. Speech-to-text transcription from audio signals
2. Audio classification using a Multi-Layer Perceptron (MLP)

The project highlights how raw audio can be transformed into meaningful representations for different machine learning tasks.

##  Objectives
- Extract textual transcripts from speech audio
- Visualize audio waveforms for signal understanding
- Perform audio feature extraction
- Train an MLP model to classify audio clips
- Demonstrate efficient audio-based machine learning pipelines

##  Dataset
- Audio samples stored as waveform signals
- Labels representing audio categories (e.g., “yes”, “no”)
- Dataset link:  
  https://drive.google.com/drive/folders/1I5Nsh8lI8uOszqh6RySq7QS9z5IEPabK

##  Methodology

### 1. Transcript Extraction (Speech Recognition)
- Audio waveform loaded and normalized
- Noise reduction applied to improve clarity
- Internal acoustic feature extraction
- Phoneme recognition using trained speech models
- Language modeling to generate readable text transcripts

### 2. Waveform Visualization
- Audio signals plotted as waveforms
- Peaks represent loud sounds; flat regions indicate silence
- Helps understand audio structure before feature extraction

### 3. Audio Feature Extraction
Each audio clip is summarized using compact numerical features:
- Audio duration
- Mean amplitude (average loudness)
- Zero Crossing Rate (signal variation / noisiness)

##  Audio Classification Using MLP
- Extracted features are scaled for neural network training
- Labels are encoded numerically
- A Multi-Layer Perceptron (MLP) is trained to learn audio patterns
- The trained model predicts the class of new audio samples

##  Technologies Used
- Python
- NumPy
- Librosa
- Matplotlib
- Scikit-learn
- Jupyter Notebook

