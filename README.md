# Python-project
 This is a sign language translator that we designed for our 3rd semester project. This program uses the landmark approach to obtain data from a set number of images to train our translator model.
 Here's a simplified use case diagram for the hand sign detection program:

1. **Collect Hand Sign Images:**
   - **Actor:** User
   - **Use Case:** Collect hand sign images (letters, numbers, etc.)
   - **Description:** The user collects a dataset of hand sign images for training and testing.

2. **Preprocess Images:**
   - **Actor:** System
   - **Use Case:** Preprocess images
   - **Description:** The system resizes, converts to grayscale, and normalizes pixel values of collected images.

3. **Extract Features:**
   - **Actor:** System
   - **Use Case:** Extract hand landmarks
   - **Description:** The system uses Mediapipe to extract hand landmarks (keypoints) from images.

4. **Train Model:**
   - **Actor:** System
   - **Use Case:** Train machine learning model
   - **Description:** The system trains a model (e.g., SVM, Random Forest) using extracted features and labels.

5. **Evaluate Model:**
   - **Actor:** User
   - **Use Case:** Evaluate model performance
   - **Description:** The user evaluates the trained model on a validation set.

6. **Test and Deploy:**
   - **Actor:** User
   - **Use Case:** Test and deploy model
   - **Description:** The user tests the model on new hand sign images and deploys it for real-time detection.
