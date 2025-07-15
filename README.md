# 🎬 Movie Recommender System using Collaborative Filtering

A real-world movie recommendation system that leverages **collaborative filtering** and **matrix factorization** to predict personalized movie preferences. Built using the **MovieLens 100k dataset**, this project demonstrates how machine learning can be applied to solve the problem of information overload on streaming platforms.


---

## 📌 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)


---

## 📖 Overview

This project simulates a real-world scenario where users rate movies, and the system learns from partial data to make personalized recommendations. The core algorithm is based on **collaborative filtering** using **low-rank matrix factorization**, widely used in production systems like Netflix and Amazon.

---

## 🎯 Dataset

- Dataset: [MovieLens 100k (ex8_movies.mat, ex8_movieParams.mat)](https://grouplens.org/datasets/movielens/)
- Total Movies: 1,682  
- Total Users: 943  
- Ratings Scale: 1 to 5  
- Sparsity: Most users rate only a small subset of available movies

---

## 🚀 Features

- Collaborative filtering cost function (with and without regularization)
- Analytical and numerical gradient computation
- Model training with L-BFGS-B optimization
- Mean normalization of ratings
- Personalized movie rating predictions
- Top-N movie recommendations

---

## 🛠️ Getting Started


### 📁 Required Files

Place the following files in your working directory:

- `ex8_movies.mat`
- `ex8_movieParams.mat`
- `movie_ids.txt`


### ✅ Install Dependencies

Make sure you have Python and the following libraries:

```bash
pip install numpy matplotlib scipy
```

Or open the Jupyter notebook in **Google Colab** which already includes all dependencies.

---

## 💡 Usage

1. Open `Untitled1.ipynb` in Google Colab or Jupyter Notebook.
2. Upload the required `.mat` files and `movie_ids.txt`.
3. Modify `my_ratings` to include your own movie preferences.
4. Run all cells to train the model and generate recommendations.

---

## 📊 Results

Example Top 10 Movie Recommendations:

```
Predicting rating 9.89 for movie Star Wars (1977)
Predicting rating 9.83 for movie Close Shave, A (1995)
Predicting rating 9.75 for movie Wrong Trousers, The (1993)
Predicting rating 9.74 for movie Fargo (1996)
...
```
---

## 🧰 Technologies Used

- Python 3.x
- NumPy
- SciPy (Optimization: L-BFGS-B)
- Matplotlib
- Google Colab / Jupyter Notebook

---


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Please open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📚 References

- [MovieLens Dataset](https://grouplens.org/datasets/movielens/)
- [Andrew Ng’s Machine Learning Course – Week 9](https://www.coursera.org/learn/machine-learning)
- Koren et al., "Matrix Factorization Techniques for Recommender Systems", IEEE Computer, 2009
