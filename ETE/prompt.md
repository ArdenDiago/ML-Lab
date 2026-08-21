I corrected only the **spelling, grammar, punctuation, and readability**. I did **not change the content, requirements, pipeline, or task structure**.

# Lab ETE

**Name:** Arden Diago
**Reg No:** 2547112
**Class:** MCA A
**Exam:** ML ETE

## Task

Your task is to develop **2 ML models**.

You have to create an `.ipynb` file for both of the tasks.

### File Structure

```text
ETE
├── ETE-1
└── ETE-2
```

Store the respective `.ipynb` files inside these folders.

I want the files to contain all the data and information that is asked for and to follow the pipelines that I have provided.

### How You Will Execute It

You will run **2 agents**, one for each task:

* Agent 1 → ETE-1
* Agent 2 → ETE-2

Let both agents complete their respective tasks. Once they are done, verify everything that has been provided and make sure all the requirements are satisfied.

---

# 1. ETE-1 – California Housing Dataset

Develop an ML pipeline for predicting house prices by combining an appropriate **dimensionality-reduction technique** with either **Support Vector Regression** or an **ensemble regression model** for the given California Housing dataset.

Justify the selected combination and discuss how dimensionality reduction may influence:

* Model accuracy
* Computational cost
* Interpretability

To load the dataset using `sklearn`, use:

```python
from sklearn.datasets import fetch_california_housing

data = fetch_california_housing()
```

For this, I wrote the pipeline as:

```text
Data
→ Data Preprocessing
→ Transforming
→ Data Splitting
→ Model Training
→ Testing the Model
→ Writing Conclusion
```

For this task, you also have to plot the appropriate graphs for the model.

Write the Python code to build and execute the complete pipeline.

---

# 2. ETE-2 – Iris Dataset

Develop and evaluate an **MLP classifier** for the Iris dataset.

Compare any **2 different hidden-layer architectures** using **cross-validation**, and assess their performance using:

* Accuracy
* Confusion Matrix

I wrote the steps as:

```text
Data
→ Preprocessing
→ Transforming
→ Data Splitting
→ Model A Training
→ Validate Model A
→ Build Model B with New Weight and Adam Layer
→ Test Model B
→ Compare Both Models
→ Plot Graphs
```

Follow this pipeline and write the required Python code.

Create appropriate plots/graphs to compare and evaluate both models.

---

## Final Verification

After both agents have completed ETE-1 and ETE-2:

1. Verify both `.ipynb` files.
2. Make sure the given pipelines have been followed.
3. Make sure all required preprocessing, transformations, training, testing, validation, and evaluation steps are included.
4. Make sure appropriate graphs are plotted.
5. Make sure ETE-1 contains the required justification and conclusion.
6. Make sure ETE-2 compares both MLP architectures using cross-validation, accuracy, and a confusion matrix.
7. Make sure all code is executable without errors.
8. Keep the final files in the following structure:

```text
ETE
├── ETE-1
│   └── ETE-1.ipynb
└── ETE-2
    └── ETE-2.ipynb
```

