# K-Nearest Neighbors (KNN) Classifier for Iris Dataset

## Team Members

- Abid Haq (abidhaqnyc@gmail.com)
- Safa Asrar (asrars20@students.ecu.edu)
- Shermar Allen (allens21@students.ecu.edu)

## Quick Start

To run the code, you'll need the following dependencies:

- Python 3.5 or higher
- scikit-learn
- matplotlib

You can install the dependencies using pip:

```bash
pip install scikit-learn matplotlib seaborn pandas

Evaluation of K Values
We performed KNN classification for K values ranging from 1 to 20, repeating the process at least five times for each K to calculate the average accuracy. The line chart displays the trend in average accuracy as K varies.

Results
The line chart illustrates the average accuracy for different K values. If multiple K values result in similar accuracies, it suggests that the model's performance stabilizes within that range of K values. The choice of the best K depends on a balance between bias and variance in the model.

.. _iris_dataset:

Iris plants dataset
--------------------

**Data Set Characteristics:**

    :Number of Instances: 150 (50 in each of three classes)
    :Number of Attributes: 4 numeric, predictive attributes and the class
    :Attribute Information:
        - sepal length in cm
        - sepal width in cm
        - petal length in cm
        - petal width in cm
        - class:
                - Iris-Setosa
                - Iris-Versicolour
                - Iris-Virginica
                
    :Summary Statistics:

    ============== ==== ==== ======= ===== ====================
                    Min  Max   Mean    SD   Class Correlation
    ============== ==== ==== ======= ===== ====================
    sepal length:   4.3  7.9   5.84   0.83    0.7826
    sepal width:    2.0  4.4   3.05   0.43   -0.4194
    petal length:   1.0  6.9   3.76   1.76    0.9490  (high!)
    petal width:    0.1  2.5   1.20   0.76    0.9565  (high!)
    ============== ==== ==== ======= ===== ====================
You can install the dependencies using pip:

```bash
pip install scikit-learn matplotlib
Run the provided Python code in a Python environment.

Iris Plants Dataset
The Iris dataset is a well-known dataset in pattern recognition literature, first used by Sir R.A. Fisher. It contains 150 instances, with 50 instances in each of three classes. The dataset consists of four numeric predictive attributes and the class label, which is the type of iris plant.

Data Set Characteristics
Number of Instances: 150 (50 in each of three classes)
Number of Attributes: 4 numeric, predictive attributes and the class
Attribute Information:
sepal length in cm
sepal width in cm
petal length in cm
petal width in cm
class:
Iris-Setosa
Iris-Versicolour
Iris-Virginica
Summary Statistics:
... (include the summary statistics here)
For more information and references about the dataset, you can refer to the dataset's official page.

Evaluation of K Values
We performed KNN classification for K values ranging from 1 to 20, repeating the process at least five times for each K to calculate the average accuracy. The line chart displays the trend in average accuracy as K varies.

Results
The line chart illustrates the average accuracy for different K values. If multiple K values result in similar accuracies, it suggests that the model's performance stabilizes within that range of K values. The choice of the best K depends on a balance between bias and variance in the model.
