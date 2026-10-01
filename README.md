# ML Learning

My personal collection of Jupyter notebooks built while studying the **Machine Learning Specialization** by Andrew Ng (DeepLearning.AI on Coursera), plus a few related math and practice labs.

The goal of this repo is simple: understand the concepts instead of just re-running the course labs. So rather than copying the original notebooks, I rebuilt each topic in my own way, with **new datasets, new scenarios, and from-scratch implementations** wherever possible. Most notebooks are self-contained and generate their own data, so no external helper files are needed.

---

## What is inside

There are **notebooks** covering the full journey from calculus basics to recommenders and reinforcement learning.

### 1. Math Foundations

| Notebook | What it covers |
|---|---|
| [Derivatives_Practice_Lab](Derivatives_Practice_Lab.ipynb) | Intuition for derivatives, arithmetic vs symbolic differentiation using SymPy |
| [Backprop_Computation_Graph](Backprop_Computation_Graph.ipynb) | Forward and backward propagation on a computation graph, chain rule, taxi fare prediction example |

### 2. Supervised Learning Basics

| Notebook | What it covers |
|---|---|
| [Salary_Linear_Regression](Salary_Linear_Regression.ipynb) | Linear regression with one variable, cost function and gradient descent, salary vs years of experience |
| [Logistic_Regression_New_Data](Logistic_Regression_New_Data.ipynb) | Logistic regression from scratch: sigmoid, cost, gradient, decision boundary, evaluation |

### 3. Neural Networks

| Notebook | What it covers |
|---|---|
| [C2_W1_Lab01_Neurons_and_Layers_reworked](C2_W1_Lab01_Neurons_and_Layers_reworked.ipynb) | A single neuron for regression and for classification (sigmoid activation) |
| [C2_W1_Lab02_CoffeeRoasting_reworked](C2_W1_Lab02_CoffeeRoasting_reworked.ipynb) | Small 2-layer network, reworked as a workout effectiveness classifier |
| [Exam_Prediction_NN_Numpy](Exam_Prediction_NN_Numpy.ipynb) | Forward propagation in NumPy, verified against TensorFlow, predicting exam success |
| [C2_W1_Assignment_Digits3v8](C2_W1_Assignment_Digits3v8.ipynb) | Binary digit recognition (3 vs 8) with both TensorFlow and NumPy implementations |
| [C2_W2_ReLU_ShippingCost](C2_W2_ReLU_ShippingCost.ipynb) | Why non-linear activations matter, modeling a tiered shipping cost with ReLU units |
| [Softmax_Custom_Practice_Lab](Softmax_Custom_Practice_Lab.ipynb) | Softmax, cost function, and sparse vs categorical cross-entropy on a 5-class dataset |
| [Multiclass_Classification_Fruit_TF](Multiclass_Classification_Fruit_TF.ipynb) | Multi-class classification in TensorFlow with a fruit sorting example |

### 4. Advice for Applying Machine Learning

| Notebook | What it covers |
|---|---|
| [C2W3_Lab_01_Model_Evaluation_and_Selection_CUSTOM](C2W3_Lab_01_Model_Evaluation_and_Selection_CUSTOM.ipynb) | Train/CV/test splits, polynomial features, model selection for regression and neural networks |
| [C2_W3_Assignment_CropYield_SoilType](C2_W3_Assignment_CropYield_SoilType.ipynb) | Bias and variance, model complexity, regularization, using crop yield and soil type data |

### 5. Decision Trees and Ensembles

| Notebook | What it covers |
|---|---|
| [Decision_Trees_Mushroom_Practice_Lab](Decision_Trees_Mushroom_Practice_Lab.ipynb) | Entropy, information gain, recursive tree building on a mushroom edibility dataset |
| [Decision_Tree_Job_Applicant_Shortlisting](Decision_Tree_Job_Applicant_Shortlisting.ipynb) | Full decision tree classifier from scratch for job applicant shortlisting |
| [Tree_Ensemble_Employee_Attrition](Tree_Ensemble_Employee_Attrition.ipynb) | Decision Tree vs Random Forest vs XGBoost on an employee attrition dataset |

### 6. Unsupervised Learning

| Notebook | What it covers |
|---|---|
| [KMeans_Clustering_CustomerSegmentation_ImageCompression](KMeans_Clustering_CustomerSegmentation_ImageCompression.ipynb) | K-means from scratch, customer segmentation, and image compression on a synthetic sunset |
| [anomaly_detection_predictive_maintenance](anomaly_detection_predictive_maintenance.ipynb) | Gaussian anomaly detection, F1-based threshold selection, predictive maintenance on sensor data |
| [PCA_Visualization_Practice](PCA_Visualization_Practice.ipynb) | PCA for visualization and exploratory data analysis, from 2D examples to high-dimensional data |

### 7. Recommender Systems

| Notebook | What it covers |
|---|---|
| [collaborative_filtering_recommender_book_edition](collaborative_filtering_recommender_book_edition.ipynb) | Collaborative filtering (loop and vectorized cost) on a synthetic book ratings dataset |
| [book_recsys_content_based](book_recsys_content_based.ipynb) | Content-based filtering with a two-tower neural network, recommendations for new readers, similar books from embeddings |

### 8. Reinforcement Learning

| Notebook | What it covers |
|---|---|
| [State_action_value_function_drone](State_action_value_function_drone.ipynb) | State-action value function Q(s, a) with the Bellman equation, campus delivery drone scenario |

---

## Tech stack

- Python 3
- NumPy, Pandas, Matplotlib
- scikit-learn, XGBoost
- TensorFlow / Keras
- SymPy
- Jupyter Notebook, ipywidgets

## Getting started

1. Clone the repository

   ```bash
   git clone https://github.com/fahadiqbal1175/ml-learning.git
   cd ml-learning
   ```

2. (Optional) Create a virtual environment

   ```bash
   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate
   ```

3. Install the dependencies

   ```bash
   pip install numpy pandas matplotlib scikit-learn xgboost tensorflow sympy ipywidgets tabulate jupyter
   ```

4. Launch Jupyter and open any notebook

   ```bash
   jupyter notebook
   ```

You can also open the notebooks directly in Google Colab or Kaggle. Most of them run top to bottom without any extra files.

## How to use this repo

- If you are following the same Coursera specialization, try each notebook after finishing the matching week, then compare it with the original lab.
- Each notebook has its own explanation, so you can read them in any order. If you are new, follow the section order above (math, basics, neural networks, and so on).
- Change the datasets and parameters and see what happens. That is exactly how I learned from these.

## Note on originality

These notebooks are inspired by the topics of the Machine Learning Specialization, but they are my own reimplementations with custom datasets and my own explanations. All credit for the course curriculum goes to Andrew Ng and the DeepLearning.AI team.

## Author

**Fahad Iqbal**
BSIT, University of Sargodha

GitHub: [@fahadiqbal1175](https://github.com/fahadiqbal1175)

If you find this repo helpful, feel free to give it a star and share your feedback.
