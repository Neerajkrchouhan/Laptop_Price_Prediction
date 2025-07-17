# Laptop_Price_Prediction
Predict laptop prices using ML algorithms
# 💻 Laptop Price Prediction using Machine Learning

This project aims to predict the price of laptops based on their specifications using machine learning models such as **Linear Regression** and **Random Forest Regressor**. It was developed as a part of my learning journey in Data Science and Machine Learning.

---

## 📂 Project Structure

- `Laptop_prediction.ipynb` – Main Jupyter Notebook containing the entire workflow
- `README.md` – Project overview, tools, and key insights

---

## 📌 Problem Statement

Laptops have a wide variety of specifications, and prices vary greatly based on features like processor, RAM, SSD, screen resolution, etc. The goal is to build a regression model that can predict the **laptop price** from its specifications.

---

## 🧹 Data Preprocessing

- Removed unnecessary symbols and units (e.g., "GB", "Hz", "inch")
- Converted textual specs to numerical values where needed
- Created new features like **PPI (pixels per inch)** from resolution
- Handled categorical features via label encoding or mapping
- Removed outliers to improve model performance

---

## 📊 Features Used

- Company  
- TypeName  
- RAM (in GB)  
- Weight (in Kg)  
- Touchscreen  
- IPS Display  
- PPI (Pixels Per Inch)  
- CPU Brand  
- HDD (in GB)  
- SSD (in GB)  
- GPU Brand  
- Operating System  

---

## ⚙️ Machine Learning Models

### 1. **Linear Regression**
- Simple baseline model
- Easy to interpret
- Struggled with non-linearity in data

### 2. **Random Forest Regressor**
- Better accuracy than linear regression
- Captures non-linear patterns
- Still room for improvement with hyperparameter tuning

---

## 📈 Evaluation Metrics

- **R² Score:** Measures how well predictions approximate real prices  
- **MAE (Mean Absolute Error):** Measures average error in prediction

---

## 📉 Current Limitations

- Model is underfitting/overfitting in some areas
- Some important features like processor generation, clock speed, brand reputation are not included
- No hyperparameter tuning yet
- Dataset size is relatively small

---

## 🛠 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📌 Future Improvements

- Use **GridSearchCV** or **RandomizedSearchCV** for hyperparameter tuning
- Try advanced models like **XGBoost**, **Gradient Boosting**
- Improve feature engineering (e.g., brand-based average pricing)
- Add more data for better generalization

---

## 📎 Sample Output

*(Include a screenshot of a prediction or model evaluation chart here)*  
You can add this later after running the notebook.

---

## 📁 How to Run

1. Clone the repository  
   `git clone https://github.com/Neerajkrchouhan/Laptop_Price_Prediction.git`
2. Navigate to the project folder  
   `cd Laptop_Price_Prediction`
3. Install required packages  
   `pip install -r requirements.txt`
4. Open the notebook  
   `jupyter notebook Laptop_prediction.ipynb`

---

## 🙋‍♂️ Author

**Neeraj Kumar**  
Aspiring Data Scientist | Machine Learning Enthusiast  
[LinkedIn]([https://www.linkedin.com/in/your-link/](https://www.linkedin.com/in/neeraj-kumar-a551a9247/)) | [GitHub]([https://github.com/Neerajkrchouhan](https://github.com/Neerajkrchouhan))

---

## 📌 License

This project is for educational purposes only. Feel free to fork and enhance it!

