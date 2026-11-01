<h1 align="center">Saksham Sharma</h1>

<p align="center">
  <i>I rebuild things from first principles, then explain them to other people.</i>
</p>

<p align="center">
  Undergrad · India · Python · Machine Learning · Research-curious
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/saksham-sharma-254812266/"><img src="https://img.shields.io/badge/LinkedIn-Saksham%20Sharma-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/Epixxs?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Epixxs-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
</p>

---

## The idea behind my work

Most ML tutorials start with `import sklearn`. I start one step earlier.

```python
# what I usually do
from sklearn.neighbors import KNeighborsClassifier   # ✗ not on my first pass

# what I do first
def knn_predict(X_train, y_train, x, k=5):
    dists = ((X_train - x) ** 2).sum(axis=1) ** 0.5   # distance, by hand
    nearest = y_train[dists.argsort()[:k]]            # k closest neighbours
    return Counter(nearest).most_common(1)[0][0]      # majority vote
```

If I can't write it without the library, I don't understand it yet. The libraries come after.

---

## The from-scratch ledger

| Rebuilt by hand | Where it ended up |
|---|---|
| K-Nearest Neighbors | Gender classification, SMS spam detection |
| Linear Regression | Diabetes prediction |
| Neural Networks | Fraud detection, customer churn |
| Clustering | Grouping Indian cities by weather and AQI |
| Classification pipelines | Titanic survival prediction |

10+ notebooks, all in **[Epixxs/machine-learning](https://github.com/Epixxs/machine-learning)**.

---

## Featured projects

### 🧠 NeuroDyad: a research paper, reproduced
Reproduces a model that applies **CEBRA** (Contrastive Embedding for Behavioral and Neural Analysis) to **dyadic EEG hyperscanning**: neural recordings from *two people talking at once*. The goal is to learn a shared neural representation that separates **speaker from listener** and picks up behavioural traits. I implemented the architecture and methodology from the paper itself, with no reference code to lean on.

---

## Stack

![Python](https://img.shields.io/badge/Python-primary-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

**Domains:** Machine Learning · Applied Mathematics · Data Science fundamentals · NLP

---

## Currently

- 🎓 **BCA, 2nd year** at Chhatrapati Shahu Ji Maharaj University (graduating 2028). Coursework includes Data Structures, Statistics, Operating Systems and more.
- 📜 **SWAYAM (NPTEL), Government of India:** *Machine Learning and Deep Learning, Fundamentals and Applications.*
- 🔬 Reading papers and rebuilding their models, with a lean toward **NLP** and research-oriented ML.

---


