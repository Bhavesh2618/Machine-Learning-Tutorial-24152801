# Machine-Learning-Tutorial-24152801

# From Perceptron to Deep Networks: Why Hidden Layers Matter

## 📌 Overview

This project presents a tutorial on neural networks, focusing on the progression from the perceptron to deep neural networks and the importance of hidden layers.

The objective is to demonstrate how hidden layers influence learning performance, model complexity, and generalisation using practical experimentation.

---

## 🎯 Objectives

- Compare perceptron, shallow, and deep neural networks  
- Evaluate their performance on a real-world dataset  
- Analyse how model depth affects learning and generalisation  

---

## 📊 Dataset

The project uses the Breast Cancer dataset from scikit-learn.

- Total samples: 569  
- Features: 30 numerical features  
- Classes:
  - Malignant (0)
  - Benign (1)

This dataset is widely used for binary classification tasks and requires minimal preprocessing.

---

## ⚙️ Methodology

The following steps were performed:

1. Train-test split (80/20)  
2. Feature scaling using StandardScaler  
3. Model training for 50 epochs  

### Models Implemented

- Perceptron-like Model  
  - No hidden layers  
  - Linear classifier  

- Shallow MLP  
  - 1 hidden layer (16 neurons)  

- Deep MLP  
  - 2 hidden layers (32 and 16 neurons)  

---

## 📈 Results

| Model              | Accuracy |
|------------------|----------|
| Perceptron-like  | 0.9649   |
| Shallow MLP      | 0.9649   |
| Deep MLP         | 0.9561   |

### Key Observations

- The dataset is largely linearly separable  
- Adding hidden layers does not significantly improve performance  
- Increasing depth may lead to slight overfitting  

---

## 📊 Visualisations

The notebook includes:

- Validation accuracy plots  
- Training loss curves  
- Accuracy comparison bar chart  
- Confusion matrices  

These visualisations explain how model depth impacts performance.

---

## 🧠 Key Insight

Hidden layers are essential for enabling non-linear learning in neural networks.  
However, increasing depth does not always improve performance.

> Model complexity should be aligned with data complexity.

---

## ♿ Accessibility

This project considers accessibility in its design:

- Plots include labels, legends, and grid lines  
- Different line styles and markers are used (not colour-dependent)  
- Bar charts include numeric values  
- High-contrast visuals improve readability  
- Figures include descriptive captions  
- Notebook includes markdown explanations  

Special care has been taken to ensure that visualisations are accessible to users with colour vision deficiencies.

---

## ⚖️ Ethical Considerations

- Machine learning models may inherit bias from data  
- In healthcare contexts, this can lead to unfair outcomes  
- Simpler models are more interpretable than deep models  
- A balance between accuracy and transparency is necessary  

---

## 🛠️ Requirements

Install dependencies:

pip install tensorflow scikit-learn matplotlib pandas

---

## ▶️ How to Run

1. Open the notebook:
   ML Tutorial Code.ipynb

2. Run all cells sequentially

3. Outputs include:
   - Model accuracy  
   - Plots  
   - Confusion matrices  

---

## 📂 Project Structure

├── ML Tutorial Code.ipynb  
├── ML Report Tutorial.pdf
├── README.md  

---

## 📚 References

- Goodfellow, I., Bengio, Y. and Courville, A. (2016) Deep Learning. MIT Press  
- Pedregosa, F. et al. (2011) Journal of Machine Learning Research  
- LeCun, Y., Bengio, Y. and Hinton, G. (2015) Nature  
- Bishop, C.M. (2006) Pattern Recognition and Machine Learning  
- Mitchell, T.M. (1997) Machine Learning  
- He, K. et al. (2016) CVPR  

---

## 👨‍🎓 Author

Student ID: 24152801  
Module: Machine Learning and Neural Networks  

---

## 📜 License

This project is created for academic purposes.  
You may reuse the code with proper attribution.

---

# 🎯 What this gives you

- ✔ Meets GitHub requirement  
- ✔ Includes methodology + results + ethics + accessibility  
- ✔ Clean academic + technical tone  
- ✔ Fully aligned with your report  

---

# 🚀 FINAL STATUS

👉 You now have:
- ✔ Report (PDF)  
- ✔ Notebook  
- ✔ README  
- ✔ Results + plots  
- ✔ Accessibility + ethics  
- ✔ References  

👉 This is complete submission package (80–85%)

---

If you want last polish:
👉 "give me github repo naming + description + tags"
