# Mushroom-Classification-ML
The project
To predict whether given mushrooms are poisonous or not.
Data
You have a dataset with information about different types of mushrooms and whether they are poisonous
or not.
Assignment
Build a PyTorch artificial neural network model to predict whether
certain mushrooms are poisonous.
The project should be written in a Google Collaborative notebook and contain:
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
the test data set.
The accuracy of the models should be calculated as a percentage - how much of
the predictions match the labels in the validation dataset. The resulting result
to convert to a decimal between 0 and 1 (0.5 means 50% accuracy, 0.95 – 95% accuracy).
datasets
Two files are given:
• Training dataset
http://ml.monov.eu/mushrooms/train_data.csv which contains a total of 21 columns:
column "id" with the identifier of the mushrooms, column "poisonous" with information about whether the mushroom
is poisonous or not (y – the mushroom is poisonous, n – the mushroom is not poisonous) and 19 columns with different
parameters (properties / features) of mushrooms. Example data:
id poisonous cap-diameter ..... ring-type habitat season
134 y 4.99 f h a
962 n 19.53 f d a
1327 y 3.84 f p a

• Testing dataset http://ml.monov.eu/mushrooms/test_data.csv which
contains 20 columns with the same fields as the training data, without the "poisonous" field.
Example data:
id cap-diameter cap-shape ..... ring-type habitat season
78 4.93 s f d a
1368 8.97 x p d a

The result result.csv should contain 2 columns with the following fields:
id – identifier of the sponge from the test data
poisonous – to contain whether the respective mushroom is poisonous or not (y or n)
Sample result:
id poisonous
128 y
2032 n
The accuracy of the generated result (result.csv) can be tested at the following address:
https://ml.monov.eu/mushrooms/test/.
