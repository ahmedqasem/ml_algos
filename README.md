# ml_algos
implementation of some machine learning algorithms namely:
<ol>
    <li>KNN</li>
    <li>Linear regression</li>
    <li>Logistic regression</li>
</ol>

in this implementation no machine learning libraries were used other than numpy and pandas

## Feature Scalingfor Both KNN and Linear regression
Training data was normalized, separately from all other dimensions.Each feature was transformed using function:</br></br> F(v) = (v –mean) / std </br></br> using the mean and std(standard deviation)of the values of that featureon the trainingdata.

## K-NN
In this task k-nearest neighbor classification was implemented.the program will be invoked with following three arguments:
<ol>
    <li>training_file: is the path name of the training file, where the training data is stored</li>
    <li>test_file: is the path name of the test file, where the test data is stored.</li>
    <li>k: specifies the value of k for the k-nearest neighbor classifier</li>
</ol>

#### K-NN Distance Calculation
 L2 distance (the Euclidean distance) was used for computing the nearest neighbors.
 
#### K-NN Classification(Testing)Stage 
For each test example a line containing the following info will be printed
<ol>
    <li>object ID</li>
    <li>predicted class</li>
    <li>true class</li>
    <li>accuracy</li>
</ol>

## Linear Regression


In this task a Linear regression was used to fit a polynomial function to the data.the program will be invoked with following three arguments:

<ol>
    <li>training_file: is the path name of the training file, where the training data is stored</li>
    <li>test_file: is the path name of the test file, where the test data is stored.</li>
    <li>degree: is an integer between 1 and 10</li>
</ol>




## Logistic Regression


In this task logistic regression was used to predict the classes of the data with the sigmoid activation function.the program will be invoked with following two arguments:

<ol>
    <li>training_file: is the path name of the training file, where the training data is stored</li>
    <li>test_file: is the path name of the test file, where the test data is stored.</li>
</ol>

