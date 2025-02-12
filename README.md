# Breast Cancer Detection Using Machine Learning

## Introduction
Breast cancer is one of the most prevalent cancers worldwide, affecting millions of individuals each year. Early detection plays a crucial role in improving survival rates. This project utilizes Machine Learning (ML) techniques to detect breast cancer using medical imaging data.

## Dataset
The dataset used in this project is the **Breast Cancer Wisconsin (Diagnostic) Data Set**, which is available in the **Scikit-learn** library and can be accessed using:

```python
from sklearn.datasets import load_breast_cancer
data = load_breast_cancer()
```
Alternatively, the dataset has been provided as a CSV file in the repository.

## Project Inspiration
This project is inspired by the research work of:
1. **Doç. Dr. Ahmet MERT** - Mekatronik Mühendisliği Bölümü, Mühendislik ve Doğa Bilimleri Fakültesi
2. **Dr. Erdem Bilgili** - Piri Reis University
3. **Dr. Aydin Akan** - Izmir Katip Celebi University, Izmir, Turkey

## Machine Learning Model Used
While multiple ML models can be employed for breast cancer detection, **Support Vector Machine (SVM)** has been found to provide the highest accuracy. The key highlights of the model’s performance are:
- **Initial Accuracy**: 96%
- **Optimized Accuracy**: 97% (after hyperparameter tuning of **C** and **Gamma**)

## Implementation Steps
1. **Data Preprocessing**: Load the dataset, check for missing values, and normalize the features.
2. **Model Selection**: Train a Support Vector Machine (SVM) classifier.
3. **Hyperparameter Tuning**: Optimize parameters using techniques like Grid Search or Random Search.
4. **Evaluation**: Use accuracy, precision, recall, and confusion matrix to evaluate model performance.
5. **Deployment (Optional)**: Deploy the model using Flask or FastAPI for real-world use.

## Installation & Usage
### Prerequisites
Ensure you have Python installed. Install the required libraries using:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

### Clone the Repository
```bash
git clone https://github.com/your-repo-url.git
cd your-repo-folder
```

### Run the Project
Execute the following command in the terminal:
```bash
python breast_cancer_detection.py
```

## Results
The optimized **SVM model** achieves an accuracy of **97%** in classifying breast cancer cases.

## Future Enhancements
- Implement **Deep Learning** models for better feature extraction.
- Deploy as a **Web Application** for real-time predictions.
- Expand dataset with more diverse medical imaging data.

## Conclusion
Working on this project has been an incredible learning experience. Machine Learning continues to revolutionize healthcare, and this project is a small step towards leveraging AI for early cancer detection.

If you enjoyed this, **don’t forget to leave a ⭐ on the repository!** 🚀

## Connect With Me
I’d love to collaborate on more ML projects. Feel free to reach out via my **GitHub Profile**.



