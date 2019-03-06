# Introduction to Machine Learning

_Notes of the free Machine Learning course from Pluralsight, found_
_[here](https://www.pluralsight.com/courses/python-understanding-machine-learning)._

To see the python scripts, first you need to have intalled _Python 3_ and _pip_.

Then, you have to install _Jupyter_ and then run the _Jupyter notebook_:

```
pip install jupyter
jupyter notebook
```

## Definition
*Machine learning*: Building a model from example inputs to make data-driven predictions vs. following strictly static program instructions.


## Machine learning logic:

Instead of "if", "case", "while" and "until", uses the data parsed to a format we can use, then we pass this formatted data to an algorithm that analyses the data (data analysis) and then it creates a model that implements the solution to solve the problem based on the data.


## Ways machines learn from data:

- **Supervised:**
    Data is labeled and has features, and we know the result we want to obtain for that data.

- **Unsupervised:**
    Search clusters of blank data and encounters groups of data that share the same traits.


|**Supervised**|**Unsupervised**|
|---|---|
|Value prediction|Identify clusters of like data|
|Needs training data containing value being predicted|Data does not contain cluster membership|
|Trained model predicts value in new data|Model probides access to data by cluster|


## Machine Learning Workflow

An **orchestrated and repeatable** pattern which systematically **transform and processes information** to **create prediction solutions**.

1. Ask the right question
2. Preparing data
3. Selecting the algorithm
4. Training the model
5. Testing the model --> If something went wrong, iterate from (2)

### Guidelines for machine learning workflow
- **Early steps are most important**. Each step depends on previous steps
- **Expect to go backwards**. Later knowledge effects previous steps
- **Data is never as you need it**. Data will have to be altered.
- **More data is better**. More data => better results.
- **Don't pursue a bad solution**. Reevaluate, fix or quit.