# Data Mining and Machine Learning (61761)

Course materials and lab exercises for **Data Mining and Machine Learning**
(כריית נתונים ומערכות לומדות), Software Engineering, Braude College of Engineering,
Semester A, 2026–2027 (תשפ"ז).

| | |
|---|---|
| Format | 5 weekly hours: 3 lecture + 2 practice |
| Credits | 4.0 |
| Tools | Python (MATLAB also accepted for the project) |
| Course site | Moodle (Braude) |

## Course goals

Principles and advanced applications of data mining: classification and clustering
of data, supervised and unsupervised learning, dimensionality reduction and deep
learning, with applications in text mining and capital-market models.

## Topics

1. Introduction, text mining problems
2. Clustering methods
   - Distribution-based methods (k-means, EM)
   - Hierarchical clustering
3. Classification methods
   - Decision trees and random forests
   - SVM
4. Artificial neural networks, linear regression, logistic regression, perceptron
5. Back-propagation
6. Introduction to deep learning
   - RNN, LSTM
   - Convolutional neural networks
   - Transfer learning
   - Word-embedding networks

## Grading

| Component | Weight |
|---|---|
| Final project | 55% |
| Midterm exam | 25% |
| Homework (labs) | 20% |

Components are weighted only if both the final project and the homework grade are 55 or above.

## AI tool usage policy

AI tools (GPT, Claude, Copilot, diffusion models) are permitted and encouraged for the
project. All AI assistance must be documented explicitly. Blind reliance on AI output is
prohibited; critical evaluation and human verification are mandatory.

## Literature

Primary
- Goodfellow, Bengio, Courville. *Deep Learning* (2016).
- Zaki, Meira. *Data Mining and Machine Learning: Fundamental Concepts and Algorithms* (Cambridge University Press, 2020).
- Rokach, Maimon, Shmueli (eds.). *Machine Learning for Data Science: Data Mining and Knowledge Discovery Handbook*, 3rd ed. (Springer, 2023).
- Žižka, Dařena, Svoboda. *Text Mining with Machine Learning: Principles and Techniques* (CRC Press, 2020).

Supplementary
- Berry, Mohamed, Yap. *Supervised and Unsupervised Learning for Data Science* (Springer, 2020).
- Aggarwal. *Neural Networks and Deep Learning: A Textbook*, 2nd ed. (Springer, 2022).

## Repository layout

```
projects/
  lab01/   Working environment, data inspection, stratified splitting
  lab02/   Text preprocessing, KNN, model evaluation
  lab03/   Distance measures, hierarchical clustering
  lab04/   K-means, Gaussian mixture models (EM), cluster validation
```

Each `labNN/` folder normally contains the assignment PDF, the starter notebook,
and the solution (notebook, script and/or PDF printout).
