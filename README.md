# alphabetic-signs-translator-
🖐️ ASL Alphabet Signs Translator

This project focuses on building a computer vision model to classify American Sign Language (ASL) alphabet signs from images.
It aims to support communication for the deaf and hard-of-hearing community by providing a foundation for real-time sign-to-text translation.

🔹 Project Overview

Dataset: ASL Alphabet dataset (hand signs for A–Z).

Goal: Recognize static hand gestures representing English alphabet letters.

Approach:

Data preprocessing (resizing, normalization).

Data visualization and class distribution analysis.

Train/test split with stratification for balanced classes.

Data augmentation to improve generalization.

CNN-based model training, evaluation, and saving for deployment.

🔹 Tech Stack

Languages & Libraries: Python, NumPy, Pandas, OpenCV, Matplotlib, Seaborn.

Machine Learning: TensorFlow / Keras (for deep learning model).

Utilities: Scikit-learn, tqdm.

🔹 Key Features

Clean and normalized dataset pipeline.

Visual exploration of dataset distribution.

CNN model trained to classify 26 alphabet signs.

Evaluation with confusion matrix, accuracy, and classification report.

✅ The trained model is saved using model.save(), so you can directly load it in your own code to build real-time sign recognition applications.

🔹 Future Work

Extend to real-time sign recognition using MediaPipe or OpenCV live capture.

Add support for dynamic signs (words/sentences).

Deploy as a web/mobile app for accessibility.
