# Real-TIme-Face-Mask-detection
 
Dataset:- https://www.kaggle.com/datasets/andrewmvd/face-mask-detection



The Project detects mask from image and webcam with more than 98% accuracy.

Modules from OpenCV is used for the detecting portion of the project whereas CNN architecture is used for the neural network part.
The project can detect masks with good accuracy under the following conditions:

Crowded places

Low quality images or stream

Low lighting(only for images)

People of different origin 

People with cloth or hands instead of mask

Different dimensions

ReLu and softmax architecture is used to prevent negetive values while learning and make the training process faster. The learning rate chosen for the model is 1e-4, with a batch size of 32 and was made to undergo 20 epochs. The final accuracy was close to 99 percent. Adam optimizer was used for this project to ensure faster detection.
 
