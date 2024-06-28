# Create-Your-Own-Spotify-Experience
The "Create Your Own Spotify Experience" project is aimed at providing users with a personalized music experience by analyzing audio features from their music files. This detailed report provides an overview of the project, its objectives, features, requirements, and usage instructions.

**Objective**
The primary objective of this project is to empower users to curate their own music experience based on their preferences and tastes. By analyzing audio features such as tempo, pitch, and rhythm, the project aims to understand the musical characteristics of individual songs and recommend similar tracks that align with the user's preferences.

**Features**
CSV Data Loading: The project includes scripts to load audio metadata from CSV files. This metadata includes information about tracks, albums, artists, genres, and more.

**Random File Selection:**
Users can select random audio files and subfolders for analysis. This feature allows for diverse and comprehensive exploration of music collections.

**Feature Extraction:**
Using the librosa library, the project extracts audio features from music files. These features include MFCC (Mel-frequency cepstral coefficients), spectral centroid, and zero-crossing rate.

**Data Storage:** 
Extracted audio features are stored in a MongoDB database for easy access and retrieval. This database serves as a repository for music-related data, facilitating efficient analysis and recommendation.

**Model Training:**
Machine learning models are trained using the extracted audio features. These models learn to identify patterns and similarities among songs, enabling accurate music recommendation.

**TensorFlow Integration:**
Deep learning models are implemented using TensorFlow for advanced music analysis and recommendation. TensorFlow provides powerful tools for building and training neural networks for music-related tasks.

**Requirements**
To run the scripts in this repository, users need to ensure the following dependencies are installed:

**Python 3
pandas
numpy
librosa
scikit-learn
pymongo
surprise
TensorFlow**
These dependencies can be installed via pip using the provided requirements.txt file.

**Usage**
To utilize the features of this project, follow these steps:

Clone the repository to your local machine.
Navigate to the repository directory.
Run the desired Python scripts according to your requirements, ensuring file paths and directory paths are updated as per your system configuration.
