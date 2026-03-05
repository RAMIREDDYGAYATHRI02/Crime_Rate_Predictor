# 🚔 Crime Rate Predictor

### Unlock Safety: Reduce Crime Rate Together

Crime Rate Predictor is a **Machine Learning based web application** that predicts crime rates across **19 Indian metropolitan cities** using historical crime data. The system helps law enforcement agencies analyze crime patterns, forecast future trends, and allocate resources efficiently to improve public safety.

---

## 📌 Project Overview

Crime prediction plays a vital role in helping authorities understand **crime trends and patterns**. By predicting possible future crime occurrences, law enforcement agencies can:

* Allocate police resources effectively
* Identify high-risk areas
* Develop better crime prevention strategies
* Improve public safety

This project uses **historical crime data from the National Crime Records Bureau (NCRB)** and applies **Machine Learning techniques** to forecast crime rates for different crime categories.

---

## 📊 Dataset Information

The dataset used in this project is prepared manually using data from the **Indian National Crime Records Bureau (NCRB)** official reports.

### Dataset Details

* **Cities Covered:** 19 Metropolitan Cities in India
* **Years Covered:** 2014 – 2021
* **Crime Categories:** 10 different types of crimes

### Crime Categories

* Murder
* Kidnapping
* Crime Against Women
* Crime Against Children
* Crime by Juveniles
* Crime Against Senior Citizens
* Crime Against SC
* Crime Against ST
* Economic Offences
* Cyber Crimes

---

## 🤖 Machine Learning Model

This system uses the **Random Forest Regression algorithm** from **Scikit-Learn**.

### How Random Forest Works

Random Forest is an **ensemble learning method** that builds multiple decision trees and combines their predictions to produce more accurate results.

### Advantages

* High prediction accuracy
* Reduces overfitting
* Handles large datasets well
* Works efficiently for structured data

### Model Performance

* **Algorithm:** Random Forest Regression
* **Accuracy:** **93.20%** on the testing dataset

---


## ⚙️ Installation

Follow these steps to run the project locally.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/RAMIREDDYGAYATHRI02/Crime_Rate_Predictor.git
```

### 2️⃣ Navigate to Project Directory

```bash
cd Crime_Rate_Predictor
```

### 3️⃣ Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```bash
python app.py
```

---

## 🚀 Usage

1. Run the application using **app.py**
2. Open the application in your browser
3. Select the following inputs:

   * City
   * Crime Type
   * Year
4. Click **Predict**
5. The predicted crime rate will be displayed on the screen.

---

## 🛠 Technologies Used

* Python
* Flask
* Scikit-Learn
* Pandas
* NumPy
* Machine Learning
* Random Forest Regression

---

## 📈 Future Improvements

* Add **real-time crime data integration**
* Implement **data visualization dashboards**
* Add **crime heatmap visualization**
* Expand predictions to **more cities**
* Integrate **deep learning models**

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to the branch

```bash
git push origin feature-name
```

5. Open a **Pull Request**

