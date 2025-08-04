# Principal Component Analysis (PCA) in Python – Portfolio Edition

This project offers a clear, step-by-step implementation of **Principal Component Analysis (PCA)** in Python. Using the classic **Iris dataset** as a practical example, this project demonstrates how dimensionality reduction can enhance data visualization and improve the efficiency of machine learning workflows.

---

## 🧩 Problem Statement

When working with modern datasets, we often encounter high-dimensional data that is challenging to visualize and computationally intensive to process. This project addresses the need to:

* Visualize high-dimensional data in 2D/3D.
* Speed up machine learning models by reducing the number of input features without losing essential information.

---

## 🧠 Solution Approach

* **Data Standardization:** All features are scaled to have zero mean and unit variance.
* **Applying PCA:** We use `scikit-learn` to extract the principal components and reduce dimensionality.
* **Visualization:** The transformed data is visualized in 2D, clearly revealing class separability.
* **Variance Analysis:** The explained variance ratio is calculated to evaluate how much information is retained.

---

## 🛠️ Technologies & Libraries

* Python 3.
* NumPy, Pandas.
* Matplotlib, Seaborn.
* `scikit-learn` (StandardScaler, PCA).

---

## 🚀 Installation & Usage

* Clone this repository or download the notebook file.
* Install dependencies with: `pip install numpy pandas matplotlib seaborn scikit-learn`.
* Run the notebook with: `jupyter notebook principal_component_analysis.ipynb`.

---

## 📊 Key Results

* Successfully reduced the original 4D Iris dataset to 2 principal components.
* Achieved more than 95% explained variance with just 2 components.
* 2D scatter plots provide clear visual separation of classes.

---

## 📸 Sample Output

https://miro.medium.com/max/875/1*7jUCr36YguAMKNHTN4Gt8A.png

---

## 🔭 Future Directions

* Extend PCA to more complex, real-world datasets.
* Combine PCA with supervised learning models (e.g., SVM, KNN) for benchmarking performance gains.
* Analyze trade-offs between dimensionality reduction and prediction accuracy.

---

## 🤝 Acknowledgements

This project was inspired by several public PCA tutorials, especially educational content by Soheil Tehranipour (Maktabkhooneh).
All code, explanations, and documentation have been fully rewritten by mehran Asgari for portfolio and educational purposes.

---

**Author:** mehran Asgari
**Email:** [imehranasgari@gmail.com](mailto:imehranasgari@gmail.com).
**GitHub:** [https://github.com/imehranasgari](https://github.com/imehranasgari).

---

## 📄 License

This project is licensed under the MIT License – see the `LICENSE` file for details.