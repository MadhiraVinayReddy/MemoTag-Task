Voice-Based Cognitive Decline Detection:

OVERVIEW:
This project aims to develop a proof-of-concept pipeline for detecting cognitive decline indicators from voice data. By analyzing audio recordings, the pipeline extracts various linguistic and paralinguistic features that may indicate cognitive impairments. The project utilizes unsupervised machine learning techniques to identify patterns in the extracted features.

FEATURES:
Audio preprocessing and normalization
Speech-to-text conversion
Extraction of cognitive decline indicators from voice data:
Pauses per sentence
Hesitation markers
Speech rate
Pitch variability
Word recall issues (placeholders)
Sentence completion
Clustering of features using KMeans
Reporting and visualization of insights

REQUIREMENTS:
To run this project, you need the following Python libraries:
librosa
SpeechRecognition
numpy
pandas
scikit-learn
matplotlib
seaborn

INSTALLATION:
You can install the required libraries using pip. Run the following command in your terminal:

bash:
pip install librosa SpeechRecognition numpy pandas scikit-learn matplotlib seaborn

USAGE:
1.Prepare Audio Files: Place your audio files in a directory and update the paths in the audio_files list in the script.
2.Run the Script: Execute the script in your Python environment. You can do this by running:

bash:
python cognitive_decline_detection.py
Replace cognitive_decline_detection.py with the name of your Python script file.

3.View Results: The script will process the audio files, extract features, perform clustering, and print a report summarizing the insights. A visualization of feature distributions will also be displayed.

EXAMPLE:
Here’s an example of how to specify audio files in the script:
if __name__ == "__main__":
    audio_files = ['path/to/audio1.wav', 'path/to/audio2.wav', 'path/to/audio3.wav']  # Add paths to your audio files
    main(audio_files)

FUTURE WORK:
1.Implement logic for detecting word substitutions and lost words.
2.Explore supervised learning methods for improved accuracy.
3.Validate the model with clinical assessments.

LICENSE:
This project is licensed under the MIT License. See the LICENSE file for more details.

ACKNOWLEDEMENTS:
1.Librosa for audio analysis.
2.SpeechRecognition for speech-to-text conversion.
3.Scikit-learn for machine learning algorithms.
