LipNet Deep Learning Model

Overview

This repository contains code for a LipNet deep learning model, originally developed from the LipNet architecture. The model is designed to process lip movements in videos and make predictions based on the observed lip features.

Features

- Video Processing: The code includes functions for loading and processing video data, extracting frames, and preparing them for input into the deep learning model.

- Alignment Processing: The alignment information associated with the videos is processed to filter out unnecessary tokens and convert the remaining tokens to numeric values.

- Deep Learning Model: The repository includes a deep learning model implemented using TensorFlow/Keras. The model architecture includes Conv3D layers, LSTM layers, Bidirectional LSTM layers, and a Dense layer.

- Streamlit App: The code is integrated into a Streamlit web application, allowing users to interactively select and view videos, observe processed frames, and see the model's predictions.

Usage

1. Setup Environment:
   - Install the required dependencies by running: `pip install -r requirements.txt`

2. Run Streamlit App:
   - Execute the Streamlit app by running: `streamlit run app.py`
   - Visit the provided URL in your web browser to interact with the application.

3. Model Loading:
   - The deep learning model is loaded using the `load_model()` function from `modelutil.py`.

Folder Structure

- data/: Contains video data and alignment files.
- models/: Stores pre-trained model weights.
- utils/: Includes utility functions for data loading and processing.

External Libraries

- OpenCV (cv2)
- Streamlit (streamlit)
- imageio
- MoviePy (moviepy)
- TensorFlow (tf)

License

This project is licensed under the MIT License.

Acknowledgements

- The LipNet model architecture is originally developed by Addison-Wesley.

Author

[Yarragoti Ravi Theja]

[Otturu Madhu Mural]
