# 🔢 Polynomial vs Linear Regression in PyTorch

This project demonstrates a comparison between a **linear model** and a **polynomial model** trained on synthetic data generated from a quadratic function.

We generate data using the equation:

\[
y = x^2 + 2x + 1 + randn()
\]
![data](https://github.com/ninadaptegit/pytorchPolynomialRegression/blob/main/data.png)
Then we train two models using PyTorch:
- 📈 **Linear Regression Model**  
- 🧮 **Polynomial Regression Model**

Finally, we compare their performance using:
- 📉 Loss score plots
- 🔍 Prediction scatter plots

---

## 📊 Results

| Model              | Loss          | Prediction Fit |
|-------------------|---------------|----------------|
| Linear Regression | Higher loss   | Poor fit       |
| Polynomial Model  | Lower loss    | Fits curve well|


### 🔹 Prediction Comparison
![Prediction Scatter](https://github.com/ninadaptegit/pytorchPolynomialRegression/blob/main/linear.png)
![Prediction Scatter](https://github.com/ninadaptegit/pytorchPolynomialRegression/blob/main/polynomial.png)


## 🛠️ Technologies Used

- PyTorch
- Matplotlib
- NumPy
- Google Colab 

---

## 📌 Key Concepts

- Data generation for regression
- Underfitting vs good fit visualization
- Manual polynomial model in PyTorch
- Training loop with gradient descent

---

## 🙌 Author

**Ninad Apte**  
Open to feedback and collaboration!

---

## 📜 License

This project is open source and free to use under the MIT License.
