# Mushroom-Classification-ML
The project</br>
To predict whether given mushrooms are poisonous or not.</br>
Data</br>
You have a dataset with information about different types of mushrooms and whether they are poisonous
or not.</br>
Assignment</br>
Build a PyTorch artificial neural network model to predict whether
certain mushrooms are poisonous.</br>
The project should be written in a Google Collaborative notebook and contain:</br>
• Description of the selected model.
• Code for reading and processing (pre-processing) the input data for training the network.
• Code to train and test the created model on given training inputs
and testing.
• Comparison of different models and training parameters such as number and size of
hidden layers, number of epochs, learning rate, as well as a table,
comparing the different results and showing the accuracy of
the different models.
• Graphs of model loss and accuracy.
• Conclude which model and parameters work best to solve the problem.
• To create an output file result.csv that contains the predicted values from
the test data set.</br>
The accuracy of the models should be calculated as a percentage - how much of
the predictions match the labels in the validation dataset. The resulting result
to convert to a decimal between 0 and 1 (0.5 means 50% accuracy, 0.95 – 95% accuracy).
datasets</br>
Two files are given:</br>
• Training dataset
http://ml.monov.eu/mushrooms/train_data.csv which contains a total of 21 columns:
column "id" with the identifier of the mushrooms, column "poisonous" with information about whether the mushroom
is poisonous or not (y – the mushroom is poisonous, n – the mushroom is not poisonous) and 19 columns with different
parameters (properties / features) of mushrooms. Example data:</br>
id poisonous cap-diameter ..... ring-type habitat season
134 y 4.99 f h a</br>
962 n 19.53 f d a</br>
1327 y 3.84 f p a</br>

• Testing dataset http://ml.monov.eu/mushrooms/test_data.csv which
contains 20 columns with the same fields as the training data, without the "poisonous" field.</br>
Example data:</br>
id cap-diameter cap-shape ..... ring-type habitat season
78 4.93 s f d a</br>
1368 8.97 x p d a</br>

The result result.csv should contain 2 columns with the following fields:</br>
id – identifier of the sponge from the test data</br>
poisonous – to contain whether the respective mushroom is poisonous or not (y or n)</br>
Sample result:</br>
id poisonous</br>
128 y</br>
2032 n</br>
The accuracy of the generated result (result.csv) can be tested at the following address:</br>
https://ml.monov.eu/mushrooms/test/.</br>
