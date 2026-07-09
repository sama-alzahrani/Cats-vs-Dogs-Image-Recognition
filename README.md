Cats vs Dogs Image Recognition

Project Description
This project uses Google Teachable Machine to train an image classification model that recognizes cats and dogs. The trained model is exported as a TensorFlow Keras model and used in Python to predict the class of an input image.

Tools Used
- Google Teachable Machine
- TensorFlow / Keras
- Python
- NumPy
- Pillow (PIL)

Project Files
- `Teachable_Machine_Classifier.py` – Python script for image prediction.
- `keras_Model.h5` – Trained model.
- `labels.txt` – Class labels.
- `test_cat.jpg` / `test_dog.jpg` – Sample test images.
- `Screenshot.png` – Prediction result.

How to Run
1. Install the required libraries:
   ```bash
   pip install tensorflow pillow numpy
   ```
2. Place the test image in the project folder.
3. Update the image path in `Teachable_Machine_Classifier.py`.
4. Run the script:
   ```bash
   python Teachable_Machine_Classifier.py
   ```

Output
The program predicts whether the image is a "Cat" or "Dog" and displays the confidence score.
