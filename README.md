## 📊 About the Dataset

### 🚢 Context

This dataset contains information about passengers aboard the **RMS Titanic**, which tragically sank during its maiden voyage in **1912** after colliding with an iceberg 🧊.  
It is one of the most widely used datasets in the data science community and serves as a benchmark for practicing **binary classification** problems. 🤖

---

### 📦 Content

The goal is to build a model that predicts **whether a passenger survived** the disaster based on features like age, sex, class, family size, and fare paid.  
This dataset is a great starting point for learning classification techniques, feature engineering, and handling missing data.

---

### 🧾 Columns Explained:

- 🆔 `PassengerId` – Unique identifier for each passenger  
- ⚰️ `Survived` – Survival status (`0` = No, `1` = Yes)  
- 🎟️ `Pclass` – Ticket class (`1` = 1st, `2` = 2nd, `3` = 3rd)  
- 🧑 `Name` – Full name of the passenger  
- 🚻 `Sex` – Gender (`male` / `female`)  
- 🎂 `Age` – Age of the passenger in years  
- 👶 `SibSp` – Number of siblings or spouses aboard  
- 🧒 `Parch` – Number of parents or children aboard  
- 🎫 `Ticket` – Ticket number  
- 💵 `Fare` – Fare paid for the ticket  
- 🛏️ `Cabin` – Cabin number (many missing values)  
- 🌍 `Embarked` – Port of Embarkation:
  - `C` = Cherbourg  
  - `Q` = Queenstown  
  - `S` = Southampton  

---

### 📉 Target Variable

- **`Survived`** – The primary feature to predict (`0` = did not survive, `1` = survived)

---
