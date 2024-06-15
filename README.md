# Pure Math Digit Recognition
a digit recognition system implemented using pure math functions in Python. This project aims to help beginners grasp the mathematics behind AI and digit recognition without relying on high-level libraries like TensorFlow or PyTorch
For further reading, check out my [post on "dev.to"](https://dev.to/devloker/mathematics-secret-behind-ai-on-digit-recognition-49lc)

# Test the project
- first install python libraries : `pillow numpy matplotlib PyQt6 keras` 
- run main python file `app.py`, a digit recognizer frame will shows up

![](https://github.com/DEVLOKER/Pure-Math-Digit-Recognition/blob/main/screenshots/qt-prediction.jpg)

- Configure the training parameters (epochs, target accuracy, and learning rate) and click on the "Train" button, or alternatively, load a pre-trained model using the "Load" button.
- Important: For optimal results, ensure you train your model until achieving a high accuracy (e.g. greater than 95%) by setting the target accuracy to 0.95. Note that reaching high training accuracy may require a significant amount of time (several minutes or longer).
- Once trained, draw a digit on the left side (e.g., 6), and click the "Recognize" button. The system will display the probability for each digit, with the highest probability indicating the most likely digit (e.g. digit: 6, probability: 97.04%).

# More info
For more information, I recommend watching this video: [But what is a neural network? | Chapter 1, Deep learning](https://www.youtube.com/watch?v=aircAruvnKk)
