# AI and ML experiments

Selected computational coursework from machine learning and artificial intelligence, organized by topic. These notebooks show small implementations, model comparisons, and experiments from 2025. This is a historical learning portfolio; outputs were cleared and training has not been rerun during preparation.

| Topic | What is here | Status |
| --- | --- | --- |
| [Fundamentals](fundamentals/) | AND perceptron | Small exercise |
| [Regression](regression/) | Manual gradient descent, two-feature regression, diabetes baseline | Selected completed cells |
| [Classification](classification/) | Iris KNN, wine ensembles, decision trees, nonlinear MLP, MNIST naive Bayes | Legacy experiments |
| [Clustering](clustering/) | Hierarchical clustering and distance-feature experiments | Selected cells; limitations documented |
| [Neural networks](neural-networks/) | CIFAR-10 CNN, power-plant and bike-sharing regression | Legacy training code; regression leakage documented |
| [Text classification](text-classification/) | Newsgroups naive Bayes, Reuters RNN/LSTM | Legacy experiments |
| [Search](search/) | A-star and greedy maze-search comparison | Historical comparison with path limitations |
| [Drafts](drafts/) | ECG anomaly detection and MRI image classification | Known evaluation/order bugs; unfinished |

Open a notebook in Jupyter with a Python environment and install only the dependencies its imports require. Typical dependencies are NumPy, pandas, matplotlib, SciPy, scikit-learn, seaborn, TensorFlow/Keras, XGBoost, and graphviz; power-plant Excel input also needs an Excel reader such as openpyxl. A tested dependency lockfile is not available. Training may be slow, and some cells download public datasets. Review code and data requirements before running. No dataset, trained weight, historical metric, or medical claim is included here.

See each topic README for inputs and known issues, and [PROVENANCE.json](PROVENANCE.json) for file-level attribution. Assignment prose was removed; course-scaffold contributions are acknowledged in [NOTICE.md](NOTICE.md).

Related public project work: [traffic crash severity](https://github.com/legooz/traffic-crash-severity-ml), [fraud detection benchmarks](https://github.com/legooz/fraud-detection-benchmarks), and [accessible text simplification](https://github.com/legooz/accessible-text-simplification). Larger separately maintained coursework projects are outside this supplement.

[Engineering portfolio](https://github.com/legooz/engineering-portfolio)
