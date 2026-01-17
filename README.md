# Inorganic-neural-synthesis
This project uses Neural Networks to assist inorganic chemists in predicting whether a desired inorganic compound can be successfully synthesized under given experimental conditions.
Lab-based inorganic synthesis often requires extensive trial-and-error, consuming time, effort, and resources. Using neural models, we aim to learn hidden chemical patterns and provide data-backed guidance before performing experiments.

PROJECT GOALS

Build a neural network that predicts reaction success probability

Model complex relationships between:

Types of precursors (oxides, salts, metals)

Reaction conditions (temperature, pressure, pH, time)

Catalysts/solvents

Elemental/structural chemical features

Reduce failed experiments by generating preliminary computational predictions

APPROACH: DEEP LEARNING FOR CHEMISTRY

Feature Engineering

Convert chemical formulas into numerical descriptors
(atomic number, electronegativity, ionic radius, oxidation states)

Encode reaction conditions and experimental environment

Neural Network Model

Fully connected deep network

Optional layers for:

Dropout (regularization)

Batch normalization

Activation functions: ReLU/sigmoid

Training

Train/test split

Hyperparameter tuning:

Learning rate

Layers & nodes

Optimizers (Adam, RMSprop)

Evaluation

Predict synthesis feasibility (0–1 probability)

Metrics:

Accuracy

F1-score

ROC-AUC

Confusion matrix

DATASET INPUTS

Known inorganic synthesis reactions from literature/databases

For each experiment:

Reactant chemical descriptors

Reaction conditions

Outcome label (Success / Failure)

🔬 Why Neural Networks?

Traditional ML models struggle with highly nonlinear chemical interactions.
Neural networks provide:

Better pattern detection

Ability to learn correlations across multiple chemical and experimental variables

Scalability with larger datasets

   IMPACT

Supports chemists by predicting which reactions are worth testing

Helps save laboratory time and costly reagents

Can expand to:

Suggest optimal reaction parameters

Explore unseen compound combinations

Integrate with materials discovery pipelines

TECH STACK

Python

TensorFlow / PyTorch

Pandas, NumPy

Matplotlib for performance plots
