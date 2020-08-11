# RoadSignClassification
In this Python project example, we built a deep neural network model that can classify traffic signs present in the image into 43 different categories. 

## Dataset
For this project, we are using the public dataset **[GTSRB - German Traffic Sign Recognition Benchmark](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)**. The dataset contains more than 50,000 images of different traffic signs classified into 43 different classes. 

### Python Libraries used
Keras
Tensorflow
OpenCV
Matplotlib
Scikit-learn
Pandas
Python Image Classification
Tkinter
Numpy

### Algorithm
•	Step 1: Capture the image.
•	Step 2: Break down the image to get 3 layers (Red, Green, Blue).
•	Step 3: Select a suitable size(5x5,3x3) and number (32,64) of function blocks.
•	Step 4: Select a suitable stride (number of pixels the function block moves after each iteration value).
•	Step 5: Run the function block through the image to identify small pixels.
•	Step 6: Repeat step 5 for all function blocks till all the pixels in the image are covered
•	Step 7: Increase the size of function block and check whether the function blocks are forming and particular pattern.
•	Step 8: Repeat step 8 until the whole picture is covered.
•	Step 9: Make the decision based on result of step 8.


### Result
After 15 epochs, we were able to achieve 94% accuracy on the training set and 95% on the validation set which is pretty good for a simple CNN based model.
