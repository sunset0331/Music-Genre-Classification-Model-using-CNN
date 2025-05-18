Music Genre Classification with CNN

This project is an end-to-end implementation of a **Music Genre Classification System** using deep learning. It processes audio files into mel spectrograms and uses a Convolutional Neural Network (CNN) to classify the genre of the music. No backend is required—just pure data preprocessing, model training, and genre prediction!


Features

- Converts `.wav` audio files into **mel spectrogram images**
- Trains a CNN on spectrograms to classify music into genres
- Validates model accuracy using a hold-out validation split
- Predicts the genre of any new music sample

 Genres Supported

The model supports classification into **11 music genres** (as per the `genres_original` folder). Ensure your dataset includes labeled subfolders such as:


Data/
├── genres_original/
│   ├── blues/
│   ├── classical/
│   ├── country/
│   └── ...


Tech Stack

- Python
- TensorFlow & Keras – Model building and training
- Librosa – Audio processing
- Matplotlib – Spectrogram visualization
- NumPy, Pandas – Data manipulation


 Model Summary

- CNN with:
  - 2 Convolutional layers + MaxPooling
  - Dense layer with Dropout
  - Output: Softmax across 11 classes

Author

Developed by Utkarsh Gaur
Feel free to fork and contribute!

