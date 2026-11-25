# Data Mining and Machine Learning

Labs and exercises for a data mining and machine learning course (Python, scikit-learn).

## What the course teaches

1. Introduction, text-mining problems
2. Clustering
   - Distribution-based methods: k-means, EM (Gaussian mixture models)
   - Hierarchical clustering
3. Classification
   - Decision trees and random forests
   - SVM
4. Artificial neural networks, linear and logistic regression, the perceptron
5. Back-propagation
6. Introduction to deep learning
   - RNN, LSTM
   - Convolutional neural networks
   - Transfer learning
   - Word-embedding networks

The course covers when to use each method, its strengths and weaknesses, how the
algorithms relate to each other (supervised vs. unsupervised), and how to choose
data, model and evaluation approach and verify the results.

## Labs (`projects/`)

| Lab | Topic | What is practiced |
|---|---|---|
| `lab01` | Data inspection & stratified splitting | Class-imbalance check, stratified vs. unstratified train/test split, multi-class stratification, 2D feature scatter plot (wine dataset) |
| `lab02` | Text preprocessing, KNN & model evaluation | `CountVectorizer`, effect of stop words on vocabulary size, K-nearest neighbors, confusion matrix, precision / recall / F1, ROC-AUC, cross-validation |
| `lab03` | Distance measures & hierarchical clustering | Euclidean vs. Manhattan distances, single / complete / average linkage, dendrograms, extracting clusters with `fcluster` |
| `lab04` | K-means, Gaussian mixture models (EM) & validation | Elbow method (inertia), silhouette score, GMM soft assignments and the most uncertain sample |

### What the files in each lab are

- `Data Mining - Lab N.pdf` - the lab instructions (the tasks to complete).
- `Data_Mining_LabN.ipynb` - the starter notebook with demo code and `TODO` cells.
- `*_solution.ipynb` - the completed notebook.
- `*.py` - the notebook exported as a plain Python script (code only).
- `*.pdf` printouts - the notebook printed to PDF: either code only (from the `.py`)
  or the full notebook with its outputs and plots.
- `.url` files - links to interactive simulators used in class.
